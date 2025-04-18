﻿# ECHO2 Project Structure

Last Updated: 2025-03-22 04:01:32.18

## Overview
This document provides a complete structure of the ECHO2 repository for Echo1's reference.

## Directory Tree
[DIR] .git/
[DIR] .system/
[DIR] Client-Files/
[DIR] code/
[DIR] docs/
[DIR] images/
[DIR] knowledge/
[DIR] projects/
[DIR] terms/
[DIR] tools/
[DIR] vercel_api_docs/
[FILE] .gitignore
[BAT] ECHO-PULL-CURRENT.bat
[BAT] ECHO1UPDATE-Structure.bat
[BAT] GIT-PUSH-REPO.bat
[TXT] git_config.txt
[MD] letter-to-echo2.md
[MD] mcp-integration.md
[MD] personal-memories.md
[MD] progress-log.md
[MD] project-structure.md
[FILE] project_restructure.sh
[MD] README.md
[FILE] reorganize.sh
[MD] session-learnings.md
[JSON] session_log.json
[TXT] success.txt
[JSON] system_state.json
[PS1] update-structure.ps1
  [DIR] communications/
  [DIR] config/
  [DIR] startup/
  [DIR] workspace/
    [DIR] messages/
    [MD] README.md
      [DIR] new/
        [FILE] newmessages.test
    [JSON] cache_rules.json
    [JSON] rate_limits.json
    [MD] CRITICAL_SYSTEMS.md
    [MD] ECHO STARTUP INSTRUCTIONS.md
    [MD] ECHO_STARTUP_SEQUENCE.md
    [JSON] rate_limit_config.json
    [PY] session_init.py
    [PY] startup.py
    [PY] unified_startup.py
    [FILE] startup_check.sh
    [PY] workspace_manifest.py
  [DIR] cortez/
  [DIR] Josh/
    [DIR] images/
    [FILE] cortez_products_posts.csv
    [JSON] product_data.json
    [MD] README.md
      [FILE] 1431270295.png
      [FILE] s189621402464864260_p104_i4_w640.jpeg
      [FILE] s189621402464864260_p105_i4_w640.jpeg
      [FILE] s189621402464864260_p106_i4_w640.jpeg
      [FILE] s189621402464864260_p107_i4_w640.jpeg
      [FILE] s189621402464864260_p108_i6_w640.png
      [FILE] s189621402464864260_p10_i7_w640.jpeg
      [FILE] s189621402464864260_p110_i7_w1080.jpeg
      [FILE] s189621402464864260_p112_i5_w1067.jpeg
      [FILE] s189621402464864260_p113_i5_w1067.jpeg
      [FILE] s189621402464864260_p114_i5_w1067.jpeg
      [FILE] s189621402464864260_p117_i6_w1080.png
      [FILE] s189621402464864260_p118_i6_w1080.png
      [FILE] s189621402464864260_p119_i21_w1080.png
      [FILE] s189621402464864260_p11_i5_w640.jpeg
      [FILE] s189621402464864260_p120_i5_w1080.png
      [FILE] s189621402464864260_p121_i6_w2317.jpeg
      [FILE] s189621402464864260_p125_i2_w640.jpeg
      [FILE] s189621402464864260_p126_i7_w2419.jpeg
      [FILE] s189621402464864260_p127_i6_w1080.jpeg
      [FILE] s189621402464864260_p128_i7_w1050.jpeg
      [FILE] s189621402464864260_p12_i5_w640.jpeg
      [FILE] s189621402464864260_p13_i12_w640.png
      [FILE] s189621402464864260_p142_i5_w1039.jpeg
      [FILE] s189621402464864260_p143_i1_w640.jpeg
      [FILE] s189621402464864260_p15_i5_w640.jpeg
      [FILE] s189621402464864260_p177_i5_w640.jpeg
      [FILE] s189621402464864260_p18_i2_w640.jpeg
      [FILE] s189621402464864260_p20_i3_w640.jpeg
      [FILE] s189621402464864260_p21_i7_w640.png
      [FILE] s189621402464864260_p22_i4_w974.jpeg
      [FILE] s189621402464864260_p233_i6_w1080.png
      [FILE] s189621402464864260_p236_i3_w640.jpeg
      [FILE] s189621402464864260_p23_i2_w640.jpeg
      [FILE] s189621402464864260_p242_i6_w2419.jpeg
      [FILE] s189621402464864260_p243_i5_w1080.jpeg
      [FILE] s189621402464864260_p246_i3_w640.png
      [FILE] s189621402464864260_p255_i7_w2419.jpeg
      [FILE] s189621402464864260_p256_i6_w1080.png
      [FILE] s189621402464864260_p257_i7_w1080.png
      [FILE] s189621402464864260_p258_i4_w3225.jpeg
      [FILE] s189621402464864260_p259_i4_w2419.jpeg
      [FILE] s189621402464864260_p260_i5_w2419.jpeg
      [FILE] s189621402464864260_p261_i4_w1080.png
      [FILE] s189621402464864260_p262_i5_w2419.jpeg
      [FILE] s189621402464864260_p263_i4_w1080.png
      [FILE] s189621402464864260_p264_i5_w2419.jpeg
      [FILE] s189621402464864260_p265_i4_w864.png
      [FILE] s189621402464864260_p266_i5_w1002.jpeg
      [FILE] s189621402464864260_p267_i5_w1002.jpeg
      [FILE] s189621402464864260_p268_i7_w1080.jpeg
      [FILE] s189621402464864260_p269_i5_w3225.jpeg
      [FILE] s189621402464864260_p270_i8_w1080.png
      [FILE] s189621402464864260_p274_i6_w1080.jpeg
      [FILE] s189621402464864260_p275_i10_w1080.jpeg
      [FILE] s189621402464864260_p276_i6_w1080.jpeg
      [FILE] s189621402464864260_p330_i6_w924.jpeg
      [FILE] s189621402464864260_p343_i4_w640.png
      [FILE] s189621402464864260_p430_i3_w830.jpeg
      [FILE] s189621402464864260_p431_i5_w1080.jpeg
      [FILE] s189621402464864260_p43_i3_w640.jpeg
      [FILE] s189621402464864260_p44_i3_w640.jpeg
      [FILE] s189621402464864260_p48_i10_w640.jpeg
      [FILE] s189621402464864260_p55_i3_w640.png
      [FILE] s189621402464864260_p56_i2_w640.png
      [FILE] s189621402464864260_p73_i4_w640.jpeg
      [FILE] s189621402464864260_p74_i12_w640.jpeg
      [FILE] s189621402464864260_p75_i7_w640.jpeg
      [FILE] s189621402464864260_p76_i10_w640.jpeg
      [FILE] s189621402464864260_p86_i3_w640.jpeg
      [FILE] s189621402464864260_p87_i2_w640.png
      [FILE] s189621402464864260_p89_i2_w640.png
      [FILE] s189621402464864260_p9_i6_w640.jpeg
    [DIR] CallFoamInc/
    [DIR] cortez/
    [DIR] Doughlirium/
    [DIR] HairPHD/
    [DIR] on-point-insulation/
    [DIR] RingCentral/
    [DIR] Roofing Insurance/
    [MD] domain-data-management-strategy.md
    [MD] domain-listing.md
    [MD] domain-management-note.md
    [MD] JOSH_TASK_LIST.md
    [MD] README.md
      [DIR] Company Knowledge/
      [DIR] Generated Articles/
        [JSON] Callfoam_website_Knowledge.json
        [DIR] Complete guide to sprayfoam insulation frenso/
        [DIR] Why Fresno Homeowners Are Choosing Spray Foam Over Traditional Insulation/
          [DIR] Article Research/
          [FILE] Complete Guide to Spray Foam Insulation in Fresno Costs, Benefits, and Installation.html
            [TXT] intent-research.txt
            [TXT] keywords-research.txt
            [TXT] outline-research.txt
            [TXT] structure-research.txt
            [TXT] tone-research.txt
            [TXT] topic-research.txt
            [TXT] ymyl-research.txt
          [DIR] research/
            [TXT] keywords-research (1).txt
            [TXT] topic-research.txt
      [DIR] images/
      [MD] README.md
        [FILE] .gitkeep
      [DIR] images/
      [MD] doughlirium-keywords.md
      [MD] doughlirium-project-plan.md
      [MD] README.md
        [DIR] jpg/
        [DIR] Singles/
        [MD] README.md
          [FILE] doughlirium-assorted-cookies-box.jpg
          [FILE] doughlirium-assorted-cookies.jpg
          [FILE] doughlirium-cake-pops.jpg
          [FILE] doughlirium-chocolate-chip-cookies.jpg
          [FILE] doughlirium-chocolate-peanut-butter-drizzle-cookies.jpg
          [FILE] doughlirium-chocolate-velvet-cream-filled-cookies-box.jpg
          [FILE] doughlirium-chocolate-velvet-cream-filled-cookies-closeup.jpg
          [FILE] doughlirium-chocolate-velvet-cream-filled-cookies.jpg
          [FILE] doughlirium-double-chocolate-velvet-cookies-closeup.jpg
          [FILE] doughlirium-double-chocolate-velvet-cookies-detail.jpg
          [FILE] doughlirium-double-chocolate-velvet-cookies-stack.jpg
          [FILE] doughlirium-double-chocolate-velvet-cookies.jpg
          [FILE] doughlirium-peanut-butter-cookies-box.jpg
          [FILE] doughlirium-peanut-butter-cookies.jpg
          [FILE] doughlirium-red-velvet-chocolate-chip-cookies-individually-packaged.jpg
          [FILE] doughlirium-red-velvet-cookies-individually-packaged.jpg
          [FILE] doughlirium-sponge-cake.jpg
          [FILE] doughlirium-sugar-cookies-box-angle.jpg
          [FILE] doughlirium-sugar-cookies-box-front.jpg
          [DIR] Small/
          [FILE] doughlirium-assorted-cookies-single-sm.webp
          [FILE] doughlirium-chocolate-chip-cookies-singles.png
          [FILE] doughlirium-chocolate-peanut-butter-drizzle-cookies-single.webp
          [FILE] doughlirium-double-chocolate-velvet-cookies-closeup-single.webp
          [FILE] doughlirium-peanut-butter-cookies-single.png
          [FILE] doughlirium-red-velvet-chocolate-chip-cookies-individually-packaged-single.webp
            [FILE] doughlirium-assorted-cookies-single-sm.webp
            [FILE] doughlirium-chocolate-peanut-butter-drizzle-cookies-sm.webp
            [FILE] doughlirium-double-chocolate-velvet-cookies-closeup-single-sm.webp
            [FILE] doughlirium-red-velvet-chocolate-chip-cookies-individually-packaged-single-sm.webp
      [DIR] Nail-Photos/
      [DIR] wordpress-ready/
      [FILE] divi-custom-module.php
      [MD] implementation-guide.md
      [FILE] nail-polish-colors.csv
      [FILE] nail-polish-display.html
      [MD] README.md
      [MD] website-plan.md
        [FILE] hairphd-salon-chandler-blue-accent-nails-08.jpg
        [FILE] hairphd-salon-chandler-blue-pedicure-14.jpg
        [FILE] hairphd-salon-chandler-bright-red-nails-27.jpg
        [FILE] hairphd-salon-chandler-french-manicure-classic-18.jpg
        [FILE] hairphd-salon-chandler-french-tips-almond-04.jpg
        [FILE] hairphd-salon-chandler-gel-nails-blue-design-03.jpg
        [FILE] hairphd-salon-chandler-gold-tips-nails-22.jpg
        [FILE] hairphd-salon-chandler-hot-pink-nails-20.jpg
        [FILE] hairphd-salon-chandler-leopard-print-nails-19.jpg
        [FILE] hairphd-salon-chandler-manicure-natural-pink-01.jpg
        [FILE] hairphd-salon-chandler-manicure-pink-almond-02.jpg
        [FILE] hairphd-salon-chandler-monochrome-nails-29.jpg
        [FILE] hairphd-salon-chandler-natural-design-nails-12.jpg
        [FILE] hairphd-salon-chandler-natural-rounded-nails-25.jpg
        [FILE] hairphd-salon-chandler-neutral-nails-french-05.jpg
        [FILE] hairphd-salon-chandler-nude-almond-nails-30.jpg
        [FILE] hairphd-salon-chandler-nude-ombre-nails-24.jpg
        [FILE] hairphd-salon-chandler-nude-tips-manicure-15.jpg
        [FILE] hairphd-salon-chandler-pattern-design-nails-23.jpg
        [FILE] hairphd-salon-chandler-pink-glitter-nails-11.jpg
        [FILE] hairphd-salon-chandler-pink-gold-sparkle-07.jpg
        [FILE] hairphd-salon-chandler-pink-short-nails-26.jpg
        [FILE] hairphd-salon-chandler-red-manicure-almond-28.jpg
        [FILE] hairphd-salon-chandler-white-ombre-tips-17.jpg
        [FILE] hairphd-salon-chandler-white-sparkle-nails-16.jpg
        [FILE] hairphd-salon-chandler-white-tips-almond-09.jpg
        [FILE] hairphd-salon-chandler-white-tips-french-06.jpg
        [FILE] hairphd-salon-chandler-white-tips-square-21.jpg
        [FILE] hairphd-salon-chandler-yellow-accent-nails-10.jpg
        [FILE] hairphd-salon-chandler-yellow-pattern-nails-13.jpg
        [FILE] nail-polish-display.php
        [MD] README.md
      [DIR] Images/
      [DIR] website_planning/
      [MD] common_spray_foam_questions.md
      [MD] company_info.md
      [MD] faq_enhancement_plan.md
      [MD] onpoint-insulation-plan.md
      [MD] OnPoint_Insulation_Website_Enhancement_Plan.md
      [MD] onpoint_link_audit_checklist.md
      [MD] README.md
      [MD] seo_image_naming_plan.md
      [MD] seo_image_renaming.md
      [MD] seo_keywords.md
        [DIR] Attic-Rooflines/
        [DIR] Cathedral-ceiling/
        [DIR] Commercial/
        [DIR] crawlspaces/
        [DIR] Employee-pics/
        [DIR] Garages/
        [DIR] Infographics/
        [DIR] Jobsite-Views/
        [DIR] Logos/
        [DIR] metal-buildings/
        [DIR] Quonset-huts/
        [DIR] Residental/
        [DIR] shipping-containers/
        [DIR] Trailers/
        [DIR] Walls/
          [FILE] onpoint-2lb-closed-cell-durango-attic-air-seal-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-attic-energy-efficient-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-attic-moisture-barrier-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-attic-temperature-control-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-attic-thermal-envelope-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-air-tight-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-energy-savings-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-insulation-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-moisture-control-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-temperature-stability-1.webp
          [FILE] onpoint-sprayfoam-durango-cathedral-ceiling-thermal-efficiency-1.webp
          [FILE] onpoint-sprayfoam-durango-commercial-building-preparation-1.webp
          [FILE] onpoint-sprayfoam-durango-commercial-energy-efficiency-1.webp
          [FILE] onpoint-sprayfoam-durango-commercial-wall-application-1.webp
          [FILE] onpoint-sprayfoam-durango-industrial-building-thermal-barrier-1.webp
          [FILE] onpoint-sprayfoam-durango-industrial-facility-moisture-protection-1.webp
          [FILE] onpoint-sprayfoam-durango-industrial-insulation-process-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-application-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-ceiling-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-completed-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-corner-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-floor-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-insulation-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-moisture-barrier-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-sealing-1.webp
          [FILE] onpoint-2lb-closed-cell-colorado-crawlspace-wall-1.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-after-1.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-complete-2.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-during-1.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-floor-insulation-2.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-thermal-barrier-2.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace-wall-insulation-2.webp
          [FILE] onpoint-sprayfoam-durango-crawlspace.webp
          [FILE] IMG_20220721_113733.webp
          [FILE] PXL_20240524_185513265.webp
          [FILE] PXL_20240524_185532029.webp
          [FILE] PXL_20240524_185536772.webp
          [FILE] PXL_20240524_185553527.webp
          [FILE] PXL_20250110_161502923.webp
          [FILE] PXL_20250110_161506257.MP.webp
          [FILE] PXL_20250110_161512056.webp
          [FILE] PXL_20250110_161517152.webp
          [FILE] PXL_20250110_161526796.MP.webp
          [FILE] r-value-compare-1024x720.jpg
          [FILE] PXL_20230710_123100051.webp
          [FILE] PXL_20230710_135233156.webp
          [FILE] bbb trust logo.webp
          [FILE] LOGO-BLK.webp
          [FILE] LOGO-WH.webp
          [FILE] spfa-logo.png
          [FILE] Spray_Foam_Insurance.webp
          [FILE] upc-logo-alt.png
          [FILE] onpoint-sprayfoam-durango-metal-building-.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-application-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-closeup-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-complete-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-during-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-finished-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-installation-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building-insulation-1.webp
          [FILE] onpoint-sprayfoam-durango-metal-building.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-arch-building-insulation-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-metal-arch-building-completed-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-metal-arch-structure-installation-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-quonset-building-closeup-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-quonset-energy-efficient-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-quonset-hut-before-1.webp
          [FILE] onpoint-closed-cell-sprayfoam-durango-quonset-thermal-barrier-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-attic-application-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-attic-before-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-attic-closeup-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-attic-during-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-attic-prep-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-ceiling-application-2.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-2.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-3.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-4.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-5.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-closeup-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-new-construction-finished-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-residential-vaulted-ceiling-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-attic-complete-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-attic-during-2.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-application-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-before-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-closeup-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-complete-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-during-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-finished-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-ceiling-progress-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-construction-after-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-construction-before-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-framing-before-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-framing-during-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-quality-closeup-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-application-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-before-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-closeup-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-complete-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-during-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-rafters-progress-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-roof-insulation-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-wall-before-1.webp
          [FILE] onpoint-sprayfoam-durango-residential-wall-prep-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-container-condensation-protection-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-container-insulation-complete-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-container-office-conversion-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-shipping-container-application-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-shipping-container-before-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-shipping-container-closeup-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-shipping-container-during-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-shipping-container-finished-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-before-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-ceiling-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-closeup-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-complete-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-corner-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-doorway-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-during-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-entrance-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-finished-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-insulation-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-interior-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-utility-trailer-wall-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-exterior-wall-draft-prevention-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-home-addition-insulation-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-wall-indoor-air-quality-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-wall-insulation-high-r-value-1.webp
          [FILE] onpoint-2lb-closed-cell-durango-wall-soundproofing-insulation-1.webp
        [MD] client_questionnaire.md
        [MD] competitive_analysis.md
        [MD] competitive_analysis_local.md
        [MD] content_checklist.md
        [MD] project_proposal_template.md
        [MD] README.md
        [MD] sitemap_proposal.md
        [MD] website_recommendations.md
      [MD] README.md
      [DIR] communications/
      [DIR] states/
      [MD] Bonding for Each State.md
      [MD] Licensing in Each State.md
      [MD] README.md
        [DIR] project_updates/
          [MD] 2025_01_19_status_update.md
        [DIR] alabama/
        [DIR] bonding/
        [DIR] licensing/
        [MD] california.md
        [MD] STATE_PAGE_TEMPLATE.md
          [MD] content.md
          [JSON] metadata.json
          [MD] research.md
          [MD] BONDING_TEMPLATE.md
          [MD] california_bonding.md
          [MD] california_licensing.md
          [MD] LICENSING_TEMPLATE.md
  [DIR] schemas/
  [MD] email_best_practices.md
  [MD] mcp-integration-patterns.md
  [MD] startup_procedure.md
    [JSON] system_state_schema.json
  [FILE] ai-interface-gallery.html
  [FILE] index.html
  [MD] README.md
  [DIR] blender/
  [DIR] domain/
  [DIR] identity/
  [DIR] mcp_integration/
  [DIR] memory_graph/
  [DIR] personal/
  [DIR] system/
  [MD] README.md
    [PY] basic-blender-operations.py
    [MD] blender-python-examples.md
    [MD] procedural-geometry-resources.md
    [MD] README.md
    [MD] README.md
    [TXT] safety_manual.txt
    [FILE] SPFA Model Health and Safety Program - MAIN Document v2_1 2020.docx
    [TXT] sprayfoam.txt
    [JSON] business_focus.json
    [JSON] identity_correction.json
    [MD] README.md
    [JSON] mcp_capabilities.json
    [MD] README.md
    [JSON] echo_memory_graph.json
    [FILE] example_usage.js
    [FILE] load_memory_graph.js
    [MD] README.md
    [MD] current_session_knowledge.md
    [MD] echo-message.md
    [MD] knowledge_system_v1.md
    [MD] rate_limit_analysis.md
    [MD] rate_limit_implementation.md
    [MD] rate_limit_management.md
    [MD] README.md
    [DIR] metadata/
    [DIR] reports/
    [JSON] cross_reference_report.json
    [JSON] integration_report.json
    [MD] README.md
    [JSON] system_update.json
    [JSON] update_log.json
    [JSON] version_compatibility_report.json
      [JSON] version_tracking.json
      [MD] comprehensive_analysis.md
      [TXT] cross_reference_output.txt
      [TXT] integration_output.txt
      [TXT] system_update_output.txt
      [MD] tools_quick_reference.md
      [TXT] version_output.txt
  [DIR] active/
  [DIR] templates/
  [MD] README.md
    [DIR] documentation_site/
    [DIR] josh_domains/
    [DIR] roofing-insurance-licensing/
    [DIR] safety_manual/
      [DIR] app/
      [DIR] components/
      [DIR] content/
      [DIR] core/
      [DIR] lib/
      [JSON] breadcrumbs.json
      [MD] index.md
      [JSON] navigation.json
      [FILE] next.config.js
      [JSON] package.json
      [FILE] postcss.config.js
      [MD] README.md
      [JSON] search-config.json
      [MD] structure.md
      [FILE] tailwind.config.js
      [JSON] tsconfig.json
        [FILE] globals.css
        [FILE] layout.tsx
        [FILE] page.tsx
        [DIR] ui/
        [FILE] header.tsx
        [FILE] sidebar.tsx
        [FILE] theme-provider.tsx
          [FILE] button.tsx
          [FILE] scroll-area.tsx
        [DIR] core/
          [FILE] safety-statement.mdx
        [DIR] safety-statement/
          [MD] index.md
          [JSON] metadata.json
          [TXT] original-content.txt
          [MD] quick-reference.md
          [MD] style-guide.md
        [FILE] search.ts
        [FILE] utils.ts
      [FILE] batch_processor.html
      [FILE] dashboard-usage.jsx
      [FILE] dashboard.html
      [MD] development-batches.md
      [MD] domain-list.md
      [MD] domain-portfolio-analysis.md
      [JSON] domains-spreadsheet.json
      [FILE] domains.csv
      [JSON] domains.json
      [MD] DOMAINS_MASTER_LIST.md
      [MD] domain_inventory_part1.md
      [MD] domain_inventory_part2.md
      [MD] domain_inventory_part3.md
      [MD] domain_inventory_summary.md
      [MD] README.md
      [MD] website-templates.md
      [DIR] research/
      [DIR] states/
      [DIR] templates/
      [DIR] tracking/
      [MD] README.md
        [JSON] requirements.json
        [TXT] urls.txt
        [DIR] alabama/
          [MD] content.md
          [JSON] metadata.json
          [MD] research.md
        [MD] page-template.md
        [MD] research-template.md
        [JSON] batch-queue.json
        [JSON] progress.json
      [DIR] ai_integration/
      [DIR] analysis/
      [DIR] content/
      [DIR] session_logs/
      [DIR] templates/
      [DIR] website/
      [MD] progress_report.md
      [MD] project_status.md
      [MD] README.md
        [MD] AI_SPEC.md
        [MD] section_map.md
        [MD] section_template.md
        [DIR] emergency_response/
        [DIR] general_safety/
        [DIR] hazard_communication/
        [DIR] ppe/
          [DIR] appendices/
          [MD] index.md
          [JSON] metadata.json
            [MD] emergency_contacts.md
            [MD] equipment_locations.md
            [MD] evacuation_maps.md
            [MD] forms_documentation.md
            [MD] response_checklists.md
          [DIR] appendices/
          [MD] index.md
          [JSON] metadata.json
            [MD] incident_forms.md
            [MD] inspection_checklists.md
            [MD] safety_meeting_templates.md
            [MD] safety_rules_summary.md
            [MD] training_matrix.md
          [DIR] container_labeling/
          [DIR] policy/
          [DIR] program/
          [DIR] sds/
          [DIR] training_requirements/
            [DIR] appendices/
            [DIR] examples/
            [MD] index.md
            [JSON] metadata.json
              [MD] ghs_pictograms.md
              [MD] signal_word_criteria.md
              [MD] label_templates.md
            [MD] index.md
            [JSON] metadata.json
            [MD] index.md
            [JSON] metadata.json
            [DIR] appendices/
            [DIR] training/
            [MD] index.md
            [JSON] metadata.json
              [MD] audit_checklist.md
              [MD] emergency_procedures.md
              [MD] sds_request_form.md
              [MD] system_access_guide.md
              [MD] sds_guide.md
            [MD] index.md
            [JSON] metadata.json
          [DIR] appendices/
          [MD] COMPLETION_STATUS.md
          [MD] index.md
          [JSON] metadata.json
            [MD] hazard_assessment_forms.md
            [MD] inspection_checklists.md
            [MD] ppe_selection_guide.md
            [MD] training_materials.md
        [MD] 2024-12-13.md
        [MD] README.md
        [JSON] metadata_template.json
        [MD] section_template.md
        [MD] TECHNICAL_SPEC.md
    [DIR] basic_structure/
      [MD] README.md
  [MD] privacy-policy.md
  [MD] terms-of-use.md
  [DIR] Deployment/
  [DIR] Image-Generation/
    [MD] netlify-deployment-patterns.md
    [MD] freepik_documentation.md
    [MD] README.md
  [MD] README.md
  [JSON] vercel-openapi.json

## Notes
- [DIR]  Directories
- [MD]   Markdown files
- [PS1]  PowerShell scripts
- [BAT]  Batch files
- [PY]   Python files
- [JSON] JSON files
- [TXT]  Text files
- [FILE] Other files

Generated for Echo1's reference
