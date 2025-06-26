# Claude Code Training Presentation Development

## Project Guidelines

This is a comprehensive Slidev presentation for Claude Code training, targeting professional developers and enterprise teams.

## Build Commands
- `pnpm dev` - Start development server with hot reload
- `pnpm build` - Build for production
- `pnpm export` - Export to PDF

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
- **Complete presentation restructure** - Reorganized from 110+ dense slides to 35 focused slides
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

## Content Organization

### Main Presentation (slides.md) - 35 slides
**Logical progression for student productivity:**
1. **Introduction & Setup** (slides 1-9): Course overview, pricing, installation, basic usage
2. **Core Productivity** (slides 10-16): Immediate-use features for daily development
3. **Workflow Tools** (slides 17-22): Session management and customization
4. **Advanced Features** (slides 23-28): Complex capabilities for power users
5. **Management** (slides 29-31): Cost, context, and permission controls
6. **Team Practices** (slides 32-35): Collaboration and best practices

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