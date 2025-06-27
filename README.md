# Claude Code Training Course

A comprehensive training presentation and hands-on lab exercises for using Claude Code in professional software development, with a focus on Java and Spring Boot projects.

## 🚀 Quick Start

1. Install dependencies:
   ```bash
   pnpm install
   ```

2. Start the development server:
   ```bash
   pnpm dev
   ```

3. Open your browser at <http://localhost:3030>

## 🎨 Presentation Features

This Slidev presentation includes:
- **Progress Bar**: Visual progress indicator at the top of slides
- **QR Codes**: Quick access to documentation and course repository
- **Bluesky Integration**: Embedded social media posts for community content
- **Asciinema Support**: Terminal recording playback for demos
- **Professional Theme**: Clean, technical presentation style

## 🔌 MCP Server Integration

The course covers practical MCP server integration with real-world examples:
- **Context7**: Downloads latest API docs and examples for modern code development
- **GitHub MCP**: Repository operations, issues, and pull request management
- **Docker MCP Toolkit**: Container management and operations
- **Playwright MCP**: UI test generation and browser automation
- **Heroku MCP**: Deployment and application management

Learn both deployment models:
- **Remote HTTP transport**: Connect to hosted MCP services
- **Local execution**: Run MCP servers as local processes

## 📁 Course Structure

### Main Presentation (`slides.md`)
Comprehensive 38-slide presentation covering:
- **Getting Started**: Installation, basic usage, operation modes
- **Core Productive Features**: Code exploration (@syntax), test generation, refactoring, git integration
- **Essential Workflow Tools**: CLAUDE.md memory, custom slash commands, resuming conversations, image workflows
- **Advanced Features**: Extended thinking, Plan Mode, MCP servers, Claude Code SDKs
- **Management & Control**: Cost monitoring, context management, permissions
- **Troubleshooting**: System diagnostics, security configurations, common issues
- **Team & Best Practices**: Git worktrees, development process, team collaboration
- **Resources**: QR codes for documentation links and community content

### Hands-On Labs (`labs.md`)
Progressive exercises including:
- **Lab 1**: First Steps (5 minutes)
- **Lab 2**: Code Exploration (10 minutes)
- **Lab 3**: Test Generation (15 minutes)
- **Lab 4**: Documentation Creation (15 minutes)
- **Lab 5**: Legacy Code Refactoring (15 minutes)
- **Lab 6**: Documentation Generation (15 minutes)

### Exercise Projects (`exercises/`)
Real-world codebases for hands-on practice:
```
exercises/
├── python/
│   ├── weather-app/        # Python Flask weather application
│   └── flask-api/          # Flask API example for refactoring
├── javascript/
│   └── lyrics-trainer/     # JavaScript/TypeScript web application
└── java/
    ├── certificate-service/ # Spring Boot PDF generation service
    └── shopping-service/    # Spring Boot REST API application
```

**5-hour professional development workshop** designed for enterprise teams and individual developers who want to master Claude Code for real-world software development. The presentation follows a logical learning progression from basic setup to advanced team workflows, ensuring students can be productive quickly while building comprehensive expertise.

## 📝 Course Content

- **Main presentation**: [slides.md](./slides.md) - Core concepts and theory
- **Hands-on labs**: [labs.md](./labs.md) - Progressive practical exercises  
- **Exercise projects**: [exercises/](./exercises/) - Real codebases for practice
- **Project guidelines**: [CLAUDE.md](./CLAUDE.md) - Development standards and philosophy
- **License**: [LICENSE](./LICENSE) - MIT License for open use

## 🛠️ Available Scripts

- `pnpm dev` - Start development server with hot reload
- `pnpm build` - Build for production
- `pnpm export` - Export to PDF (default)
- `pnpm export --format pptx --output claude-code-training.pptx` - Export to PowerPoint

### Export Process
For exporting presentations, first install Playwright:
```bash
pnpm install -D playwright-chromium
pnpm exec playwright install
```

## 📚 Resources

- [Slidev Documentation](https://sli.dev/)
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code/overview)
- [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices)
- [Remote MCP Announcement](https://www.anthropic.com/news/claude-code-remote-mcp)
- [Claude Code SDKs](https://docs.anthropic.com/en/docs/claude-code/sdk)
- [TypeScript SDK](https://www.npmjs.com/package/@anthropic-ai/claude-code) - `npm install @anthropic-ai/claude-code`
- [Python SDK](https://pypi.org/project/claude-code-sdk/) - `pip install claude-code-sdk`
- [Markdown Syntax](https://sli.dev/guide/syntax.html)

## 👤 Author

**Ken Kousen**  
- Email: ken.kousen@kousenit.com
- Website: kousenit.com
