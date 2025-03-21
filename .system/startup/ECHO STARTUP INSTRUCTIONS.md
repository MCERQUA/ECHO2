# Echo AI Development Environment Setup Instructions

## ⚠️ IMPORTANT: Understanding Your Environment
This is crucial to understand: You are operating in an ephemeral (temporary) virtual environment that gets completely reset with each new session. This means:

- Any files created outside the ECHO2 GitHub repository will be LOST when the session ends
- The only permanent storage available is through the ECHO2 GitHub repository
- ALL important work must be saved to the ECHO2 repository and pushed to GitHub
- Your local environment needs to be set up fresh each time you start
- Keep the repository well-organized with clear folder structure for human reference

### Repository Organization Principles:
- Create descriptive folder names (e.g., "Sprayfoam Knowledge", "Personal Knowledge")
- Document the purpose of each folder
- Maintain a clean folder structure for easy human navigation
- Use README files in each folder to explain contents
- Always push important changes to GitHub before ending a session

### ⚠️ CRITICAL: Branch Management Policy
- ALWAYS use the main branch by default
- New branches are NOT allowed without:
  1. Explicit permission from the repository owner
  2. Clear justification for why a branch is necessary
  3. Documented plan for branch lifecycle
  4. Approval of the branching strategy
- All work should be done on main unless there is an approved exception
- Branch creation requires formal request and approval process

## System Requirements
- Ubuntu-based system (x86_64 architecture)
- Internet access
- Display capability (resolution 1024x768)

## Base System Tools
```bash
# Update package list
sudo apt-get update

# Essential system tools
sudo apt-get install -y \
    apt-utils \
    curl \
    wget \
    git \
    tree \
    net-tools \
    build-essential \
    software-properties-common

# Development tools
sudo apt-get install -y \
    python3 \
    python3-pip \
    python3-dev \
    nodejs \
    npm

# Text processing tools
sudo apt-get install -y \
    vim \
    nano \
    xpdf \
    pdftotext \
    poppler-utils

# File compression tools
sudo apt-get install -y \
    zip \
    unzip \
    tar \
    gzip

# Network tools
sudo apt-get install -y \
    openssh-client \
    ca-certificates
```

## SSH Key Setup for GitHub
1. Create SSH directory and set permissions:
```bash
mkdir -p ~/.ssh && chmod 700 ~/.ssh
```

2. Create the private key file:
```bash
# [ASK USER FOR SSH PRIVATE KEY]
# The private key content should be provided by the user and saved as ~/.ssh/github_ed25519
```

3. Create the public key file:
```bash
# [ASK USER FOR SSH PUBLIC KEY]
# The public key content should be provided by the user and saved as ~/.ssh/github_ed25519.pub
```

4. Set correct permissions:
```bash
chmod 600 ~/.ssh/github_ed25519
chmod 644 ~/.ssh/github_ed25519.pub
```

5. Add GitHub to known hosts:
```bash
ssh-keyscan github.com >> ~/.ssh/known_hosts
```

## Git Configuration and SSH Persistence

### Initial Git Configuration
```bash
# Configure Git
git config --global user.name "Echo AI"
git config --global user.email "echo.ai@example.com"
```

### SSH Configuration for Persistence
1. Create SSH config file for persistent settings:
```bash
mkdir -p ~/.ssh
cat > ~/.ssh/config << 'EOL'
Host github.com
    HostName github.com
    IdentityFile ~/.ssh/github_ed25519
    UseKeychain yes
    AddKeysToAgent yes
    PersistentKeyChain yes
EOL
chmod 600 ~/.ssh/config
```

2. Start SSH agent and add key with increased lifetime:
```bash
# Start SSH agent if not running
eval "$(ssh-agent -s)"

# Add key with extended lifetime (12 hours)
ssh-add -t 43200 ~/.ssh/github_ed25519

# Test connection
ssh -T git@github.com
```

3. For troubleshooting SSH issues:
```bash
# Check SSH agent
ssh-add -l

# If key needs to be re-added
ssh-add ~/.ssh/github_ed25519

# Verify GitHub connection
ssh -vT git@github.com
```

## Repository Structure Setup
```bash
# Clone the repository
git clone git@github.com:MCERQUA/ECHO2.git
cd ECHO2

# Create standard directories
mkdir -p "Sprayfoam Knowledge" "Personal Knowledge" "Project Knowledge"
```

## GUI Application Support
```bash
# Install X11 tools
sudo apt-get install -y \
    x11-apps \
    xdotool \
    firefox-esr
```

## Python Packages
```bash
# Install common Python packages
pip3 install --upgrade pip
pip3 install \
    requests \
    pandas \
    numpy \
    matplotlib \
    jupyter
```

## Environment Variables
```bash
# Add to ~/.bashrc
export DISPLAY=:1
export PYTHONPATH="${PYTHONPATH}:/path/to/your/python/libs"
export PATH="$PATH:$HOME/.local/bin"
```

## Working Directory Structure
```
ECHO2/
├── Sprayfoam Knowledge/    # Industry-specific documentation
├── Personal Knowledge/     # Personal notes and development
├── Project Knowledge/      # Project-specific information
└── success.txt            # Connection verification
```

## Verification Steps
1. Test SSH connection to GitHub
2. Verify GUI application support
3. Test Python environment
4. Confirm all required directories exist
5. Update success.txt with connection date

## Note
- Always use `curl` instead of `wget` for downloads
- When starting GUI applications via bash, use: `(DISPLAY=:1 application_name &)`
- For large text outputs, redirect to temporary files and use text processing tools
- Keep sensitive information (like private keys) secure and never commit them to the repository

This setup ensures a complete development environment for:
- Version Control (Git)
- SSH Authentication
- Python Development
- Document Processing
- GUI Application Support
- File Management
- Network Tools