# AI GitHub Interface Website

An intelligent web interface that allows users to interact with GitHub repositories through natural language using our remote MCP server.

## 🎯 Features

- **Natural Language GitHub Operations**: Create files, update repos, manage issues through chat
- **Real-time AI Assistant**: Powered by remote MCP server at `https://github-mcp-remote.metamike.workers.dev/sse`
- **Secure Authentication**: Uses existing GitHub OAuth flow
- **Repository Management**: Browse, create, update files across repositories
- **Modern UI**: Clean, responsive interface with real-time feedback

## 🏗️ Architecture

```
Frontend (React/HTML) 
    ↓
Backend API (Node.js/Express)
    ↓
Remote MCP Server (Cloudflare Workers)
    ↓
GitHub API
```

## 🚀 Deployment

- **Frontend**: Netlify/Vercel
- **Backend**: Railway/Render
- **MCP Server**: Already deployed to Cloudflare Workers

## 📁 Project Structure

```
ai-github-interface/
├── frontend/              # React frontend
│   ├── src/
│   │   ├── components/    # UI components
│   │   ├── pages/        # Page components
│   │   └── services/     # API services
│   └── public/           # Static assets
├── backend/              # Node.js API server
│   ├── routes/          # API routes
│   ├── services/        # MCP connection logic
│   └── middleware/      # Auth & validation
└── docs/                # Documentation
```

## 🔧 Technology Stack

- **Frontend**: React, Tailwind CSS, Axios
- **Backend**: Node.js, Express, WebSocket
- **MCP Integration**: Server-Sent Events (SSE)
- **Authentication**: GitHub OAuth
- **Deployment**: Netlify + Railway/Render

## 📝 Development Status

- [x] Project structure created
- [ ] Frontend UI development
- [ ] Backend MCP integration
- [ ] Authentication flow
- [ ] Deployment setup
