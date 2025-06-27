# Claude Code Training Presentation Development

## Project Guidelines

This is a comprehensive Slidev presentation for Claude Code training, targeting professional developers and enterprise teams.

## Build Commands
- `pnpm dev` - Start development server with hot reload
- `pnpm build` - Build for production
- `pnpm export` - Export to PDF (default)
- `pnpm typecheck` - Run TypeScript type checking (if needed)
- `pnpm lint` - Run linting checks (if configured)

## Export Process
The presentation supports multiple export formats for different use cases:

### Setup (one-time)
```bash
pnpm install -D playwright-chromium
pnpm exec playwright install
```

### Export Commands
```bash
# Standard exports (already in repository)
pnpm export                                                    # → slides-export.pdf (13MB)
pnpm export --format pptx --output claude-code-training.pptx   # → claude-code-training.pptx (31MB)

# Optional: Export with click animations (larger files)
pnpm export --with-clicks --output slides-with-clicks.pdf
pnpm export --format pptx --output claude-code-training-with-clicks.pptx --with-clicks
```

### Distribution Strategy
- **Live presentations**: Use Slidev (`pnpm dev`) for professional animations and navigation
- **O'Reilly Learning Platform**: Upload PPTX format for course platform compatibility
- **Student materials**: Provide both PPTX (editable/compatible) and PDF (compact/printable)

## Content Standards
- Focus on technical capabilities and practical examples
- Developer-focused content without marketing language
- Clean, simple slide structure following technical presentation patterns
- Progressive disclosure using v-clicks
- Code examples where appropriate
- Concise, direct explanations

## Slide Design Principles
- **Clean, technical style** - Similar to academic/technical conferences
- **Minimal bullet points** - Each slide covers one focused concept
- **Progressive disclosure** - Use v-clicks for step-by-step revelation
- **No decorative elements** - Focus on content, not visuals
- **Consistent structure** - Simple title + focused content
- **Code-focused** - Include relevant code examples and commands

## Current Architecture
- Built with Slidev framework using Seriph theme
- Main content in slides.md with 35 focused slides
- Comprehensive coverage from basics to advanced features
- Integration of latest Claude Code features (Plan Mode, Remote MCP, SDKs)
- Logically organized for optimal learning progression

## Recent Major Updates
- **Complete presentation restructure** - Reorganized from 110+ dense slides to 38 focused slides
- **Logical learning progression** - Reordered content for immediate productivity:
  1. **Getting Started** (Installation, Basic Usage, Operation Modes)
  2. **Core Productive Features** (Code Exploration, Test Generation, Refactoring, Git Integration)
  3. **Essential Workflow Tools** (CLAUDE.md memory, Custom Slash Commands, Resuming Conversations, Images)
  4. **Advanced Features** (Extended Thinking, Plan Mode, MCP, SDKs)
  5. **Management & Control** (Cost Monitoring, Context Management, Permissions)
  6. **Team & Best Practices** (Git Worktrees, Best Practices, Team Collaboration)
- **Comprehensive feature coverage** - Added all major Claude Code capabilities:
  - Cost monitoring (/cost command) and context management (/compact)
  - Extended thinking with verification patterns and token cost awareness
  - Resuming conversations (--continue/--resume flags)
  - Working with images (drag/drop, copy/paste workflows)
  - Configuring permissions (enterprise controls, /permissions UI)
  - Git worktrees for parallel sessions
  - Enhanced memory management (project vs user CLAUDE.md files)
  - Custom slash commands with $ARGUMENTS and scoping details
- **Split complex slides** - Broke down dense content (e.g., Custom Slash Commands split into concept + implementation)
- **Eliminated marketing content** - Maintained only essential pricing information
- **Added presentation enhancements**:
  - Progress bar component for visual slide progress tracking
  - QR code functionality for easy link sharing (docs and repository)
  - Bluesky integration for embedding social media posts
  - Clean resource slides with important links
- **Added troubleshooting section**:
  - System health diagnostics with `/doctor` command
  - Global configuration settings
  - Security-focused aliases and tool restrictions
  - Common issues and solutions
  - WSL requirement for Windows users

## Content Organization

### Main Presentation (slides.md) - 38 slides
**Logical progression for student productivity:**
1. **Introduction & Setup** (slides 1-9): Course overview, pricing, installation, basic usage
2. **Core Productivity** (slides 10-16): Immediate-use features for daily development
3. **Workflow Tools** (slides 17-22): Session management and customization
4. **Advanced Features** (slides 23-28): Complex capabilities for power users
5. **Management** (slides 29-31): Cost, context, and permission controls
6. **Troubleshooting** (slides 32-34): Diagnostics, security, and common issues
7. **Team Practices** (slides 35-38): Collaboration, best practices, and resources

### Hands-On Labs (labs.md)
1. Lab 1: First Steps (5 minutes)
2. Lab 2: Code Exploration (10 minutes)
3. Lab 3: Test Generation (15 minutes)
4. Lab 4: Documentation Creation (15 minutes)
5. Lab 5: Legacy Code Refactoring (15 minutes)
6. Lab 6: Advanced Workflows (15 minutes)

### Exercise Projects (exercises/)
- **Python**: weather-app (Flask), flask-api (refactoring practice)
- **JavaScript**: lyrics-trainer (TypeScript web app)
- **Java**: certificate-service (Spring Boot PDF), shopping-service (REST API)

## Presentation Delivery Notes
- 5-hour course format with hands-on exercises
- July 2025 first delivery planned
- Target audience: Professional developers and enterprise teams
- Optimized for students to become productive quickly while building comprehensive expertise
- Include latest features as "cutting-edge" content

## Technical Setup
### Slidev Addons Installed
- `slidev-component-progress` - Progress bar at top of slides
- `slidev-addon-qrcode` - QR code generation for links (replaced buggy @katzumi version)
- `slidev-addon-bluesky` - Embed Bluesky social media posts
- `slidev-addon-asciinema` - Terminal recording playback (ready for future demos)

### Known Issues
- Initial QR code addon (@katzumi/slidev-addon-qrcode) had caching bugs - replaced with slidev-addon-qrcode
- Peer dependency warnings with slidev-component-progress can be ignored
- Bluesky posts require full DID format (e.g., `did:plc:...`)

### MCP Server Integration Examples
Real-world MCP servers covered in presentation:
- **Context7**: Latest API documentation and examples for modern development
- **GitHub MCP**: Repository operations, issues, and pull request management
- **Docker MCP Toolkit**: Container management and operations
- **Playwright MCP**: UI test generation and browser automation
- **Heroku MCP**: Deployment and application management

Shows both deployment models:
- **Remote HTTP transport**: `claude mcp add --transport http context7 https://mcp.context7.com/mcp`
- **Local execution**: `claude mcp add context7 -- npx -y @upstash/context7-mcp`

### Security Review Notes
- Presentation files contain no sensitive information
- Exercise projects contain intentional security vulnerabilities for educational purposes:
  - SQL injection examples in Flask API
  - Hardcoded credentials for demonstration
  - XSS vulnerabilities in shopping service
  - These are clearly marked as training exercises