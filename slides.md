---
theme: seriph
background: https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Claude Code Training
  
  By Kenneth Kousen
  
  Learn more at [KouseniT](https://kousenit.com)
drawings:
  persist: false
transition: slide-left
title: "Claude Code Training"
mdc: true
slidev:
  slide-number: true
  controls: true
  progress: true
css: unocss
---

<style>
.slidev-page-num {
  display: block !important;
  opacity: 1 !important;
  visibility: visible !important;
  position: fixed !important;
  bottom: 1rem !important;
  right: 1rem !important;
  z-index: 100 !important;
  color: #666 !important;
  font-size: 0.875rem !important;
}
</style>

# Claude Code Training

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---

# Contact Info

Ken Kousen  
Kousen IT, Inc.

- ken.kousen@kousenit.com
- http://www.kousenit.com
- http://kousenit.org (blog)
- Social Media:
  - [@kenkousen](https://twitter.com/kenkousen) (twitter)
  - [@kenkousen@foojay.social](https://foojay.social/@kenkousen) (mastodon)
  - [@kousenit.com](https://bsky.app/profile/kousenit.com) (bluesky)
- *Tales from the jar side* (free newsletter)
  - https://kenkousen.substack.com
  - https://youtube.com/@talesfromthejarside

---

# Course Overview

<v-clicks>

- **Duration**: 5-hour intensive workshop
- **Topics Covered**:
  - Installation and CLI basics
  - Code exploration and understanding
  - Testing and quality assurance
  - Git operations and version control
  - Advanced features (Plan Mode, MCP, SDKs)
- **Hands-on Labs**: Multiple exercises with real codebases
- **Prerequisites**: Command-line experience, development background

</v-clicks>

---

# Pricing Plans

<v-clicks>

- **Pro Plan** - $20/month
  - ~10-40 prompts per 5 hours
  - Sonnet 4 only
- **Max Plan 5x** - $100/month
  - ~50-200 prompts per 5 hours
  - Sonnet or Opus 4
- **Max Plan 20x** - $200/month
  - ~200-800 prompts per 5 hours
  - Sonnet or Opus 4
- **Note**: Opus 4 uses 5x more credits than Sonnet 4
- **Limits reset**: Every 5 hours

</v-clicks>

---

# What is Claude Code?

<v-clicks>

- Command-line AI tool for development
- Context-aware codebase understanding
- Autonomous and collaborative modes
- Multi-language support
- Integrated git operations
- Test generation and documentation

</v-clicks>

---

# Installation

<v-clicks>

- Install via npm: `npm install -g @anthropic-ai/claude-code`
- Or download from GitHub releases
- Set API key: `export ANTHROPIC_API_KEY="your-key"`
- Verify: `claude --version`

</v-clicks>

---

# Basic Usage

<v-clicks>

- Start Claude Code: `claude`
- Natural language prompts
- File-specific requests
- Multi-step workflows

</v-clicks>

---

# Operation Modes

<v-clicks>

- **Command Mode** (default) - Interactive conversation
- **Auto-Accept Mode** (Shift+Tab) - Autonomous execution
- **Plan Mode** (Shift+Tab+Tab) - Review plans before execution

</v-clicks>

---

# Code Exploration

<v-clicks>

- Find files, functions, patterns
- Understand system architecture
- Trace dependencies
- Identify frameworks

</v-clicks>

---

# Test Generation

<v-clicks>

- Unit test creation
- Edge case identification
- Integration tests
- Mock object setup

</v-clicks>

```bash
"Create unit tests for the UserService"
"Add tests for error scenarios"
```

---

# Refactoring Capabilities

<v-clicks>

- Multi-file operations
- Smart refactoring
- Pattern replacement
- Modern syntax adoption

</v-clicks>

---

# Git Integration

<v-clicks>

- Commit message generation
- Branch management
- Merge conflict resolution
- Pull request creation

</v-clicks>

```bash
"Commit these changes with an appropriate message"
"Create a pull request for this feature"
```

---

# Documentation Generation

<v-clicks>

- Inline comments
- README files
- API documentation
- Architecture docs

</v-clicks>

---

# Debugging Workflows

<v-clicks>

- Error message analysis
- Stack trace navigation
- Configuration debugging
- Integration debugging

</v-clicks>

---

# Model Context Protocol (MCP)

<v-clicks>

- Standard protocol for AI-to-system connections
- Tool integration (APIs, databases, services)
- Context enhancement for better AI responses
- Security controls and permissions

</v-clicks>

---

# MCP Server Examples

<v-clicks>

- **GitHub MCP** - Repository operations, issues, PRs
- **Sentry MCP** - Error tracking and debugging
- **Linear MCP** - Project management integration
- **Docker MCP** - Container management
- **Database MCP** - Query and schema operations

</v-clicks>

---

# Plan Mode

<v-clicks>

- Press `Shift+Tab+Tab` to activate
- Claude presents implementation plan
- Review strategy before execution
- Approve or modify approach
- Perfect for complex changes

</v-clicks>

---

# CLAUDE.md Files

<v-clicks>

- Project-specific instructions
- Coding standards and conventions
- Architecture decisions
- Testing preferences
- Build commands and workflows

</v-clicks>

---

# Custom Slash Commands

<v-clicks>

- Automate repetitive tasks
- Team standardization
- Domain-specific actions
- Quick shortcuts

</v-clicks>

```bash
# Create .claude/commands directory
mkdir -p .claude/commands

# Create a command file
touch .claude/commands/spring-service.md
```

---

# Best Practices

<v-clicks>

- **Be specific** - Clear, detailed instructions work better
- **Provide context** - Explain your goals and constraints
- **Iterate gradually** - Make incremental improvements
- **Use examples** - Show desired patterns or styles

</v-clicks>

---

# Development Process

<v-clicks>

- Start with clean git state
- Commit checkpoints regularly
- Review changes before accepting
- Test generated code thoroughly

</v-clicks>

---

# Team Collaboration

<v-clicks>

- Share CLAUDE.md configurations
- Document successful patterns
- Review AI-generated code together
- Establish team conventions

</v-clicks>

---

# Thank You!

<div class="text-center">

## Questions?

<div class="pt-12">
  <span class="text-6xl"><carbon:logo-github /></span>
</div>

**Kenneth Kousen**  
*Author, Speaker, Java & AI Expert*

[kousenit.com](https://kousenit.com) | [@kenkousen](https://twitter.com/kenkousen)

</div>