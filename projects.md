[« Back to Resume](./README.md)
# Projects

List of projects I worked on so far. For skills, see the [main resume](./README.md#skills).

## AI & Innovation Projects

* **SOZO AI Briefing Agent**
   * Internal AI product with PDF analysis, web research (Tavily), interactive question-based workflows, SSE streaming
   * Configurable system prompts, lead scoring capabilities, multi-format export (PDF/DOCX)
   * Built with Next.js 16, React 19, OpenAI Assistants API, Supabase, Tavily, Tailwind CSS
* **SOZO AI Chatbot** (WordPress Plugin + n8n Pipeline)
   * RAG-based chat plugin with n8n document ingestion workflow
   * n8n pipeline: Google Drive knowledge folder sync, file type routing (PDFs vs Google Docs/Word/text), PDF extraction (100-page limit), text splitting, embedding generation, batch insertion to Supabase vector storage, processed file management
   * Built with PHP 8.2+, WordPress Plugin API, OpenAI API, Supabase (vector storage), Google Drive API, n8n
* **WellChild Awards AI Workflow** (n8n)
   * Multi-agent AI workflow system for charity award nomination processing
   * Eligibility Agent: 4-step assessment (medical eligibility, safeguarding, category fit, UK location)
   * Scoring Agent: Quality scoring framework (0-100) across impact, evidence quality, category alignment, narrative strength
   * Gravityforms webhook intake, Airtable data storage, Google Docs prompt management, Slack notifications
   * Structured output parsing, batch processing with loop control, anonymisation
   * Built with n8n, OpenAI GPT-5.2, OpenAI 4.1 Mini, Airtable, Google Docs, Slack
* **AI Tool Standardisation Framework**
   * Formal approval process with team voting, manager sign-off, and evaluation periods
   * Privacy guidelines, evidence collection processes, and productivity measurement
   * Documented 15-40% time savings on block development, 60-80% on documentation
* **Figma MCP Integration**
   * Claude Code integration with automatic technology detection (Tailwind, React, HTML, Blade)
   * Design configuration extraction and web-to-Figma conversion workflows
   * Design system analysis: font sizing, line heights, component sizing, SVG standards
* **AI Skills Architecture**
   * Global vs project-specific skills for WordPress (Radicle) and Shopify
   * Frontend/backend agent specialisation with role-specific documentation
   * Published to GitHub (sozo-design/ai-agent-docs)
* **Vector Database Research**
   * Pinecone architecture for intelligent property search
   * Multimodal data design (property metadata, 360 views) for AI-powered discovery
   * Multi-LLM strategy evaluation (GPT, Claude, Gemini, Copilot)
* **Claude Code Account Switcher** - [cc-account-switcher](https://github.com/dr5hn/cc-account-switcher)
   * Multi-account management tool for Claude Code (macOS, Linux, WSL)
   * Secure keychain integration, export/import, interactive mode, switch history
   * Built with Shell/Bash

## SOZO Design Projects

### Recent Projects (2025-2026)

* **WoodScanner v2**
   * Custom marketplace with white label dynamic styling (CSS variables + ACF + shell scripts)
   * Seller onboarding workflows, client training sessions, multi-language support
   * Product search, data mapping, volume/pack size management
* **Schneider Electric / DistributorIQ**
   * Interactive prototype deployed on Vercel
   * GitHub Actions CI/CD (replacing manual Vercel CLI)
   * Feedbucket integration for client feedback
* **Solton Manor**
   * Online cost calculator (80% completion)
   * PDF quote generator, CRM integration, calendar blocking
* **Inspirational Group**
   * Blog import, block development, design handover
   * Full site build and finalisation
* **Gala Hospitality**
   * ZOHO CRM integration, live deployment, after-live snags
* **Postsaver**
   * QBC migration (US to UK), WooCommerce v10 upgrade across both sites
* **Teamwork CLI** (@sozo-design/teamwork-cli)
   * npm package replacing scattered bash scripts and Python tools
   * Support for Projects API and Desk API
* **HTML Forms Akismet Plugin** (sozo-design/html-forms-akismet)
   * Spam protection plugin, v1.0.1 released

### Major Website Developments

#### E-commerce Projects
* **Sky Garden** - Advanced Pallet Calculator, WooCommerce enhancements, performance optimisation
* **Indulge Brownies** - Complete e-commerce solution with custom product management
* **Just Fabrics** - Algolia Sort integration, contracts management system, security enhancements

#### Corporate Websites
* **Windrush Car Storage** - Achieved 100% SEO score, car storage management system
* **Medicair** - Phase-wise launch, third-party service integrations
* **G13+** - PHP and JavaScript enhancements, custom features

#### Service Portals
* **Agasco** - Service portal with customer management and booking functionality

### Technical Implementations

#### Integration Projects
* **PLH** - Clerk Integration, woo-recaptcha v3 for spam prevention
* **OSN** - Hubspot integration, PT-X Direct Debit
* **TOSN** - Stripe payment system, RSS Feed functionality

#### Infrastructure Projects
* **Platform Migrations** - WP Cluster to Kinsta, Cloudways migration, Bitbucket to GitHub migration
* **Testing** - Cypress and Playwright testing frameworks, automated QA processes

### Innovation Projects
* **McCarthy** - Skip booking plugin architecture
* **EZI Klamp** - Custom quote solution replacing YITH Quote plugin
* **Base Theme** - Radicle-based theme with SOZOUi and Sozo WP Core

## Open Source Products

### Country State City - Geo-Data Platform
A widely adopted open source geo-data ecosystem (9.3k+ stars, 3k+ forks) covering 250 countries, 5,299 states, and 153,765 cities. Freemium API, packages, and developer tooling.

* **Core Database** - [countries-states-cities-database](https://github.com/dr5hn/countries-states-cities-database)
   * Dataset in 11+ formats: JSON, MySQL, PostgreSQL, SQLite, MongoDB, XML, YAML, CSV, GeoJSON, TOON
   * Built with PHP, Python, MySQL, GitHub Actions
* **API Platform** - [csc-app](https://github.com/dr5hn/csc-app) - [app.countrystatecity.in](https://app.countrystatecity.in)
   * Freemium subscription API with dashboard, API key generation, and usage management
   * API: Express.js, Prisma (PostgreSQL + MySQL), Bull queues, Redis, Sentry, Passport (GitHub OAuth), Zod
   * Frontend: React, Vite, TypeScript, TanStack Query, Zustand, Radix UI, Recharts, Tailwind CSS
* **Main Website** - [csc-website-v2](https://github.com/dr5hn/csc-website-v2) - [countrystatecity.in](https://countrystatecity.in)
   * Built with Next.js 15 (App Router), Tailwind CSS 4, Radix UI, Three.js/React Three Fiber, Motion
* **Documentation** - [csc-docs](https://github.com/dr5hn/csc-docs) - [docs.countrystatecity.in](https://docs.countrystatecity.in)
   * Built with Mintlify and MDX
* **Export Tool** - [csc-export-tool](https://github.com/dr5hn/csc-export-tool) - [export.countrystatecity.in](https://export.countrystatecity.in)
   * One-time export service with freemium credit-based system
   * Built with Express.js, MongoDB (Mongoose), Redis, Passport (GitHub OAuth), DodoPayments, JSZip, Winston, Sentry
* **Changelog System** - [csc-changelog](https://github.com/dr5hn/csc-changelog) - [changelog.countrystatecity.in](https://changelog.countrystatecity.in)
   * Automated change tracking system monitoring 157k+ changes across countries, states, and cities
   * Individual country changelogs, statistics dashboard, JSON API access, 24-month retention
   * Built with HTML, CSS, JavaScript, JSON
* **npm Packages**
   * [@countrystatecity/countries](https://www.npmjs.com/package/@countrystatecity/countries) / [@countrystatecity/timezones](https://www.npmjs.com/package/@countrystatecity/timezones)
   * Built with TypeScript, tsup, Vitest
* **Python Package**
   * [countrystatecity-countries](https://pypi.org/project/countrystatecity-countries/) - Built with Pydantic, pytest, mypy, ruff

### Country State City Encyclopedia - [countrystatecity.org](https://countrystatecity.org)
* [csc-org-website](https://github.com/dr5hn/csc-org-website) - Geographic encyclopedia built on the CSC dataset
   * Built with Next.js 16, React 19, Tailwind CSS, Lucide Icons

### iLoveJSON - [ilovejson.com](https://ilovejson.com)
* [iLoveJSON](https://github.com/dr5hn/ilovejson) - JSON utility tool for converting JSON to any format (CSV, HTML, XML, TOML, and more). Inspired by iLovePDF.
   * Built with Next.js, NextAuth, Prisma (PostgreSQL), Radix UI, Tailwind CSS, TypeScript, Docker

### Step Up Grow - Investment Portal
* [step-up-grow](https://github.com/dr5hn/step-up-grow) - SIP and one-time investment management portal
   * Client: React 18, TypeScript, Shadcn UI (Radix UI), TanStack Query, TanStack Table, React Hook Form, Recharts, Tailwind CSS, Zod
   * API: Node.js, Express.js, TypeScript, Prisma (PostgreSQL), JWT Auth, PDFKit, Zod

### SkyWork Borivali - Co-working Space Website
* [skywork](https://github.com/dr5hn/skywork) - [skyworkborivali.com](https://skyworkborivali.com) - Premium co-working space website
   * Responsive website with image gallery, Google Maps integration, encrypted contact details
   * Built with HTML, CSS, JavaScript, Bootstrap, jQuery, Swiper.js, Magnific Popup

## Other Projects by Technology

### Laravel / LAMP / LEMP
* Enablr (eDetailing Application for Pharma Industries)
* [CanMan](https://github.com/dr5hn/canman) (Canvas Project Management Application) *Confidential
* TheGreatNext (Adventure travel website)
* [parcelg](https://github.com/dr5hn/parcelg) - ParcelG Admin APP with API - Built with Infyom Laravel Generator
* [courierman](https://github.com/webgeeks-in/courierman) - Courier Management System - Built with Laravel
* [free2lance](https://github.com/webgeeks-in/free2lance) - Freelance Project Management Portal
* [csc-api](https://github.com/dr5hn/csc-api) - API for countries-states-cities-database - Built with Lumen *Private

### MEAN / MERN
* Slingshot (Test preparation application for JEE and MHCET students) *MVP
* [Vis-Board](https://github.com/dr5hn/vis-board) (Data Visualisation Dashboard - Built with MongoDB, Express, Angular & Node.js) *Confidential
* WeOne (Micro Earning Platform from Advertisements - Built with MongoDB, Strapi, Node.js, Neo4j, React & Flutter) *MVP

### Core PHP
* Just Fabrics - The largest Fabrics Designer in the UK
* Econolytics - Analyst Job Portal

### Python / Django
* [Kirkus Reviews](https://www.kirkusreviews.com/) - Book Reviews Writing & Publishing Website - Built with Django, Python & MySQL
* [clockify\_bulk\_insert](https://github.com/dr5hn/clockify_bulk_insert) - Automate bulk time entry insertion in Clockify

### Ionic
* SafeQR - Companion app to store vehicle details and documents inside a QR

### Shopify Apps
* [Automated SMS Plugin for Shopify](https://apps.shopify.com/sms-marketing-automation)
* [Custom Shopify app for Sabbath mode](https://apps.shopify.com/shabbat-mode)

### React / Next.js
* [scratch-n-win](https://github.com/dr5hn/scratch-n-win) - Scratch and Win with Firebase Auth - Built with Next.js
* [Simple-CRUD](https://github.com/dr5hn/Simple-CRUD) - CRUD Using React JS with PHP, MySQL

### Drupal
* Nom-Nom - School Lunch Providers - Built with Drupal 9.x

### Phaser.js
* [spin-a-wheel](https://github.com/dr5hn/spin-a-wheel) - Wheel of Fortune game

### Alexa Skill
* [who-is](https://github.com/dr5hn/who-is) - Alexa Skill to pull domain info, expiry and hosting info

### Developer Tools & Automation
* [backup-action](https://github.com/valerianpereira/backup-action) - GitHub Action to backup MySQL, MongoDB and PostgreSQL databases
* [backup.sh](https://github.com/dr5hn/backup.sh) - Backup MySQL & MongoDB shell script with email reports
* [nginx-conf](https://github.com/dr5hn/nginx-conf) - NginX configurations for Laravel, Node.js, WordPress, Angular & Strapi
* [server-setup](https://github.com/dr5hn/server-setup) - Server setup guide for Ubuntu

### HTML to WordPress
* [B N Jewellers](http://www.bnjewellers.in/)
* [Swadhaar FinAccess](http://www.swadhaar.org/)
* [IVY Pro School](https://ivyproschool.com/)
* [Sun Capital Services](https://suncapitalservices.co.in/)
* [RBL Finserve](https://www.rblfinserve.com/)

### WordPress
* [My Mountains](https://my-mountains.ch/)
* [Shri Rupa Manjree Institute](https://srmi.iskcondesiretree.com/)
* [Embee](https://embee.co.in/)
* [Arphi](http://arphi.com/)
* [CashE](https://www.cashe.co.in/)
* [Tridhaatu](https://tridhaatu.com/)
* [Kerala Ayurved](https://keralaayurved.com/)
* Windrush Car Storage
* G13+
* Agasco

### WooCommerce
* Sky Garden
* Indulge Brownies

### Codeigniter
* Media Maggi Tutorials

### API Integrations
Hubspot, Stripe, WordPress REST API, Leadsquared, Shopify, Cashfree, Razorpay, Google Adsense & Analytics, TimaticWeb (IATA), Moodle, Sendgrid, MSG91, AWS SES & SNS, PayUMoney, Facebook, Twitter, GitHub, Webedify, Authorize.net, and more.

### HTML Websites
* [Perfect Forwarders](http://www.perfectforwarders.com/)
* Rae ISP

[« Back to Resume](./README.md)
