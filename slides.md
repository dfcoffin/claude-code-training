---
theme: seriph
background: https://source.unsplash.com/1920x1080/?coding,ai
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Claude Code Training Course
  Agentic Coding with AI - Professional Development Workshop

  Learn to leverage Claude Code for enterprise Java/Spring development
drawings:
  persist: false
transition: slide-left
title: Claude Code Training Course
mdc: true
---

# Claude Code Training Course
## Agentic Coding with AI

**Ken Kousen**  
*Author • Speaker • Developer*

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Learn to leverage Claude Code for professional development workflows <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/kousen" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github></carbon-logo-github>
  </a>
</div>

---
layout: default
---

# About Ken Kousen

## Author • Speaker • Developer

<div class="mt-8">

<v-clicks>

- **President of Kousen IT, Inc.** - Training and consulting
- **Author of multiple books** including *Modern Java Recipes*, *Mockito Made Clear*, and *Help Your Boss Help You*
- **Java Champion**
- **Expert in:** Java, Spring, Gradle, Groovy, Kotlin, and AI/ML
- **International speaker** at conferences worldwide
- **Computer Science professor** at Trinity College, Hartford, CT
- **30+ years** of enterprise software development
- **Trainer and consultant** for Fortune 500 companies

</v-clicks>

</div>

<div class="mt-12 p-6 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-center">
  <strong class="text-lg">🎯 Mission:</strong> Making technical concepts accessible and practical for real-world development teams
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Course Overview

## What You'll Learn
- Master Claude Code fundamentals
- Navigate and understand codebases
- Implement effective testing strategies
- Streamline Git operations
- Create professional documentation
- Debug complex issues efficiently

## Course Structure
- **5 hours** of core content
- **Hands-on exercises** throughout
- **Real-world examples** from production code
- **Best practices** from industry use

::right::

<div class="text-center mt-8">
  <img src="https://images.unsplash.com/photo-1517180102446-f3ece451e9d8?w=400&h=300&fit=crop" class="rounded-lg shadow-lg mb-4"/>
</div>

<v-clicks>

- ✅ **Based on real experience**
- ✅ **Production Java/Spring projects**
- ✅ **Anthropic team insights**
- ✅ **Practical workflows**

</v-clicks>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: default
---

# Installation & Setup

## Installation Methods

```bash {all|1-2|4-5|all}
# Install via npm
npm install -g @anthropic-ai/claude-code

# Or download from GitHub releases
# https://github.com/anthropic-ai/claude/releases
```

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## Authentication Setup

```bash {1-2|4-5}
# Set your API key
export ANTHROPIC_API_KEY="your-api-key-here"

# Or configure interactively
claude auth login
```

</div>

<div>

## Verify Installation

```bash
claude --version
claude --help
```

</div>

</div>

<div class="mt-8 p-4 bg-yellow-100 rounded-lg border-l-4 border-yellow-500">
  <strong>💡 Pro Tip:</strong> Add your API key to your shell profile (.bashrc, .zshrc) for persistent access
</div>

---
layout: default
---

# Basic Command Structure

## Core Commands

```bash {1-2|4-5|7-8|all}
# Navigate to your project
cd /path/to/your/spring-boot-project

# Start Claude Code
claude

# Or start with specific instructions
claude "Help me understand this Spring application"
```

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## Command Syntax

<v-clicks>

- **Natural language prompts** - Describe what you want to accomplish
- **File-specific requests** - Reference files directly  
- **Multi-step workflows** - Chain complex operations

</v-clicks>

</div>

<div>

<v-click>

<div class="text-center p-6 bg-blue-50 rounded-lg border-2 border-dashed border-blue-300">
  <h3 class="text-lg font-bold text-blue-800">🚀 Demo Time!</h3>
  <p class="text-blue-600">Let's see Claude Code in action with a Spring Boot project</p>
</div>

</v-click>

</div>

</div>

---
layout: default
---

# 🚀 First Hands-On Exercise

## Get Claude Code Running in Your Project

**Time: 5 minutes**

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

### Your Tasks

<v-clicks>

1. **Navigate to any code project** on your machine
2. **Start Claude Code** with `claude`
3. **Ask it to explore** the project structure
4. **Try a simple request** like "explain this codebase"

</v-clicks>

</div>

<div>

<v-click>

### Example Commands

```bash
# Navigate to your project
cd ~/my-spring-project

# Start Claude Code
claude

# Try these prompts:
"Give me an overview of this project"
"What files are most important here?"
"Explain the main entry point"
```

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-green-50 rounded-lg border-l-4 border-green-500 text-sm">
  <strong>🎯 Goal:</strong> Get comfortable with the basic Claude Code interface and see it analyze a real project
</div>

<div class="mt-3 p-3 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>💡 Don't have a project handy?</strong> Try it in this presentation's directory - Claude Code can analyze any codebase!
</div>

---
layout: default
---

# 💰 Claude Code Pricing & Plans

## Understanding Your Options

<div class="grid grid-cols-3 gap-6 mt-8">

<div class="p-6 bg-blue-50 rounded-lg border-2 border-blue-200">

### Pro Plan
**$20/month**

<v-clicks>

- **~10-40 prompts** per 5 hours
- **Sonnet 4 only**
- Best for small repos (<1,000 lines)
- Light development work

</v-clicks>

</div>

<div class="p-6 bg-purple-50 rounded-lg border-2 border-purple-200">

### Max Plan - 5x
**$100/month**

<v-clicks>

- **~50-200 prompts** per 5 hours
- **Sonnet or Opus 4**
- Medium to large repos
- Regular development work

</v-clicks>

</div>

<div class="p-6 bg-green-50 rounded-lg border-2 border-green-200">

### Max Plan - 20x
**$200/month**

<v-clicks>

- **~200-800 prompts** per 5 hours
- **Sonnet or Opus 4**
- Large enterprise repos
- Heavy development work

</v-clicks>

</div>

</div>

<v-click>

<div class="mt-6 p-3 bg-yellow-100 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>⚠️ Important:</strong> Opus 4 uses 5x more credits. Limits reset every 5 hours.
</div>

</v-click>

<v-click>

<div class="mt-3 p-3 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>💡 Pro Tip:</strong> Start with Pro plan, then upgrade based on usage patterns and project complexity
</div>

</v-click>

---
layout: default
---

# What is Claude Code?

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## Agentic Coding Assistant

<v-clicks>

- **Command-line AI tool** that works directly in your development environment
- **Context-aware** - understands your entire codebase
- **Autonomous capabilities** - can work independently or collaboratively
- **Multi-language support** - Java, Python, JavaScript, and more

</v-clicks>

</div>

<div>

<v-click>

### Key Capabilities
```mermaid
graph TD
    A[Claude Code] --> B[Code Generation]
    A --> C[Intelligent Debugging]
    A --> D[Test Creation]
    A --> E[Documentation]
    A --> F[Git Operations]
    A --> G[Codebase Exploration]
```

</v-click>

</div>

</div>

<v-click>

### Perfect For
Spring Boot applications • Complex enterprise codebases • API development • Microservices architectures • Testing workflows

</v-click>

---
layout: default
---

# Code Search & Understanding

## Codebase Navigation

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Intelligent search** - Find files, functions, patterns
- **Architecture overview** - Understand system structure
- **Dependency mapping** - Trace relationships
- **Pattern recognition** - Identify common frameworks

</v-clicks>

</div>

<div>

<v-click>

### Real-World Example: Spring AI Project

```bash
# Example commands:
"Show me the main application structure"
"Find all REST controllers in this project"
"Explain the Spring AI configuration"
"Trace the flow from controller to service layer"
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>🔍 Anthropic Insight:</strong> Data Infrastructure team replaces traditional data catalogs with Claude Code for codebase discovery
</div>

---
layout: default
---

# 🔍 Hands-On Exercise: Explore a Codebase

## Practice Code Search & Understanding

**Time: 10 minutes**

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

### Your Mission

<v-clicks>

1. **Choose a project** (Spring Boot, Node.js, Python, etc.)
2. **Ask Claude to map the architecture**
3. **Find specific components** (controllers, services, etc.)
4. **Trace execution flows**

</v-clicks>

</div>

<div>

<v-click>

### Try These Prompts

```bash
"What's the overall architecture of this project?"

"Find all the REST endpoints in this codebase"

"Show me how data flows from API to database"

"What design patterns are used here?"

"Identify the main configuration files"
```

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-green-50 rounded-lg border-l-4 border-green-500 text-sm">
  <strong>🎯 Goal:</strong> Experience Claude Code's ability to quickly understand and explain complex codebases
</div>

<div class="mt-3 p-3 bg-purple-100 rounded-lg border-l-4 border-purple-500 text-sm">
  <strong>⭐ Pro Tip:</strong> Start with high-level questions, then dive deeper into specific areas
</div>

---
layout: default
---

# High-Level Project Analysis

<div class="grid grid-cols-2 gap-8">

<div>

## Spring Boot Projects

<v-clicks>

- Configuration classes
- Service layer design
- Data access patterns
- Security implementation

</v-clicks>

</div>

<div>

## Claude Code Analysis

<v-clicks>

- Framework detection
- Design pattern identification
- Best practice validation
- Improvement suggestions

</v-clicks>

</div>

</div>

<v-click>

<div class="mt-2">

### Example: MCP Server Analysis
<p class="text-sm">From the GitHub MCP Server project:</p>

<div style="transform: scale(0.75); transform-origin: top center; margin-top: -20px;">

```mermaid
graph LR
    A[Spring Boot 3.5] --> B[MCP Integration]
    A --> C[Service Layer]
    A --> D[GitHub Operations]
    B --> E[Process Management]
    C --> F[Modern Java Features]
    F --> G[Records]
    F --> H[Virtual Threads]
```

</div>

</div>

</v-click>

---
layout: two-cols
layoutClass: gap-16
---

# File Editing & Refactoring

## Editing Capabilities

<v-clicks>

- **Multi-file operations** - Change multiple files simultaneously
- **Smart refactoring** - Maintain code consistency
- **Pattern replacement** - Apply changes across codebase
- **Modern syntax adoption** - Upgrade to newer language features

</v-clicks>

::right::

<div class="grid grid-cols-1 gap-4">

<div>

### Java Modernization

<v-clicks>

- Convert to Records
- Add Virtual Threads
- Switch expressions
- Pattern matching

</v-clicks>

</div>

<div>

### Spring Updates

<v-clicks>

- Configuration properties
- Dependency injection patterns
- Test modernization
- Security improvements

</v-clicks>

</div>

</div>

<div class="mt-8 text-center p-4 bg-purple-50 rounded-lg border-2 border-dashed border-purple-300">
  <h3 class="text-lg font-bold text-purple-800">🔄 Live Demo</h3>
  <p class="text-purple-600">Refactoring a Spring service to use modern Java features</p>
</div>

---
layout: default
---

# Bug Fixing Strategies

## Systematic Debugging Approach

<v-clicks>

- **Error analysis** - Understand stack traces and exceptions
- **Root cause identification** - Trace issues to source
- **Fix implementation** - Apply targeted solutions
- **Verification** - Ensure fixes work correctly

</v-clicks>

<v-click>

## Real Examples from Security Engineering

<div class="mt-6 p-6 bg-gradient-to-r from-red-50 to-orange-50 rounded-lg border-l-4 border-red-500">

**Infrastructure Debugging:**
- ⚡ Reduced debugging time from **10-15 minutes to 5 minutes**
- 📊 Stack trace analysis with documentation context
- 🔍 Control flow tracing through complex codebases

</div>

</v-click>

<div class="mt-6 p-4 bg-yellow-100 rounded-lg border-l-4 border-yellow-500">
  <strong>💡 Pro Tip:</strong> Use Claude Code to explain error messages in plain English before attempting fixes
</div>

---
layout: default
---

# Testing & Quality Assurance

<div class="grid grid-cols-2 gap-8">

<div>

## Test Generation

<v-clicks>

- **Unit test creation** - Comprehensive test coverage
- **Edge case identification** - Find scenarios you missed
- **Integration tests** - End-to-end validation
- **Mock object setup** - Proper test isolation

</v-clicks>

</div>

<div>

<v-click>

### Example: Spring AI Training Course Tests

```bash
# Generate tests for service layer
"Create unit tests for the FilmographyService class"

# Test Spring AI integration
"Write integration tests for the ChatClient configuration"

# Test edge cases
"Add tests for error scenarios in the AI service"
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>🎯 Anthropic Teams:</strong> "Claude automatically includes missed edge cases, completing what would normally take significant mental energy in minutes"
</div>

---
layout: default
---

# The EPCC Workflow: Explore → Plan → Code → Commit

## A Systematic Approach to Development with Claude Code

<div class="grid grid-cols-4 gap-3 mt-6">

<div class="p-3 bg-blue-50 rounded-lg border-l-4 border-blue-400 text-sm">

### 🔍 Explore
<v-clicks>

- Read relevant files
- Understand structure
- Identify patterns
- Map architecture

</v-clicks>

</div>

<div class="p-3 bg-purple-50 rounded-lg border-l-4 border-purple-400 text-sm">

### 📋 Plan
<v-clicks>

- Define objectives
- Break down tasks
- Identify risks
- Create strategy

</v-clicks>

</div>

<div class="p-3 bg-green-50 rounded-lg border-l-4 border-green-400 text-sm">

### 💻 Code
<v-clicks>

- Implement systematically
- Follow patterns
- Write tests first
- Maintain quality

</v-clicks>

</div>

<div class="p-3 bg-orange-50 rounded-lg border-l-4 border-orange-400 text-sm">

### 📦 Commit
<v-clicks>

- Review changes
- Generate messages
- Document decisions
- Create pull requests

</v-clicks>

</div>

</div>

<v-click>

<div class="mt-6 p-4 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-lg border-l-4 border-blue-500 text-sm">

**🔑 Key Principle:** "Claude performs best when it has a clear target to iterate against"

**Example:** Explore codebase → Plan OAuth2 addition → Implement security config → Commit with docs

</div>

</v-click>

---
layout: default
---

# ✅ Hands-On Exercise: Generate Tests

## Practice Test Creation with Claude Code

**Time: 15 minutes**

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

### Your Challenge

<v-clicks>

1. **Pick a class or function** in your project
2. **Ask Claude to generate unit tests**
3. **Request edge case tests**
4. **Add integration tests**
5. **Review and run the tests**

</v-clicks>

</div>

<div>

<v-click>

### Example Prompts

```bash
"Create comprehensive unit tests for this UserService class"

"Add edge case tests for null inputs and empty strings"

"Generate integration tests for the REST API endpoints"

"Create mock objects for the database dependencies"

"Add performance tests for this method"
```

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-green-50 rounded-lg border-l-4 border-green-500 text-sm">
  <strong>🎯 Goal:</strong> Experience edge case identification and comprehensive test suite creation
</div>

<div class="mt-3 p-3 bg-yellow-100 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>💡 Bonus:</strong> Ask Claude to explain its test case choices - learn best practices!
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Test-Driven Development

## Traditional TDD

<v-clicks>

1. Write failing test
2. Write minimal code  
3. Refactor
4. Repeat

</v-clicks>

## Claude Code TDD

<v-clicks>

1. Describe requirements
2. Generate comprehensive tests
3. Implement solution
4. Refactor and optimize

</v-clicks>

::right::

<v-click>

## Security Team's Transformation

<div class="space-y-4">

<div class="p-4 bg-red-50 rounded-lg border-l-4 border-red-400">
  <strong>Before:</strong> "design doc → janky code → refactor → give up on tests"
</div>

<div class="p-4 bg-green-50 rounded-lg border-l-4 border-green-400">
  <strong>After:</strong> "Ask Claude for pseudocode → guide through TDD → periodic check-ins → reliable, testable code"
</div>

</div>

</v-click>

<div class="mt-6 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>⭐ Best Practice:</strong> Ask Claude to generate tests before writing code for better autonomous operation
</div>

---
layout: default
---

# Git Operations

## Git Integration Features

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Commit message generation** - Meaningful, conventional commits
- **Branch management** - Create and manage feature branches
- **Merge conflict resolution** - Intelligent conflict solving
- **Pull request creation** - Automated PR generation

</v-clicks>

</div>

<div>

<v-click>

### Example Workflow

```bash
# Commit with generated message
"Commit these changes with an appropriate message"

# Create feature branch
"Create a new branch for the AI service refactoring"

# Resolve conflicts
"Help me resolve the merge conflicts in the service layer"

# Generate PR description
"Create a pull request for this feature"
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-purple-100 rounded-lg border-l-4 border-purple-500">
  <strong>🤖 Product Team Example:</strong> GitHub Actions integration automatically addresses PR comments like formatting issues or function renaming
</div>

---
layout: default
---

# Code Base Exploration

## Techniques for Understanding New Projects

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Component identification**  
  Find key architectural elements
- **Execution flow tracing**  
  Follow request/response paths
- **Pattern recognition**  
  Identify frameworks and conventions
- **Dependency analysis**  
  Understand module relationships

</v-clicks>

</div>

<div>

<v-click>

### Example Commands

```bash
"Give me an overview of this Spring Boot application"

"Show me the data flow from REST endpoints to database"

"Identify all the configuration files and their purposes"

"Find examples of how authentication is implemented"
```

</v-click>

</div>

</div>

---
layout: default
---

# Onboarding Acceleration

## Transforming New Developer Experience

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

### Real Impact from Inference Team

<v-clicks>

- 📚 **Codebase comprehension in seconds** instead of asking colleagues
- 🏗️ **Find relevant files** and understand architecture quickly  
- ⚡ **Reduce onboarding time** from weeks to days

</v-clicks>

</div>

<div>

<v-click>

### Benefits for Everyone

- **New team members** become productive faster
- **Senior developers** experience less interruption
- **Self-service learning** through AI assistance
- **Consistent onboarding** across all projects

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-gradient-to-r from-green-50 to-blue-50 rounded-lg border-l-4 border-green-500">
  <strong>🚀 Result:</strong> Transform onboarding from a weeks-long process requiring constant mentorship to self-directed exploration in days
</div>

---
layout: default
---

# Documentation Generation

<div class="grid grid-cols-2 gap-8">

<div>

## Documentation Types

<v-clicks>

- **Inline comments** - Code-level documentation
- **README files** - Project overviews and setup guides
- **API documentation** - Service and endpoint descriptions
- **Architecture docs** - System design explanations

</v-clicks>

</div>

<div>

### Real Example: MCP Server README

<v-click>

**Your GitHub MCP Server README demonstrates excellent documentation:**

</v-click>

<v-clicks at="2">

- ✅ Clear installation instructions
- ✅ Configuration examples
- ✅ Feature descriptions with examples
- ✅ Troubleshooting guidance
- ✅ Technology stack explanation

</v-clicks>

</div>

</div>

<div class="mt-8 p-4 bg-indigo-100 rounded-lg border-l-4 border-indigo-500">
  <strong>📝 Claude.md Files:</strong> Create detailed workflow documentation to guide Claude Code's behavior in your projects
</div>

---
layout: default
---

# 📝 Hands-On Exercise: Create Documentation

## Practice Documentation Generation

**Time: 15 minutes**

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

### Documentation Challenge

<v-clicks>

1. **Choose an undocumented project** or component
2. **Generate a README.md** file
3. **Add inline code comments**
4. **Create API documentation**
5. **Write setup instructions**

</v-clicks>

</div>

<div>

<v-click>

### Powerful Prompts

```bash
"Create a comprehensive README for this project"

"Add detailed comments to this complex method"

"Generate API documentation for these endpoints"

"Write installation and setup instructions"

"Create a troubleshooting guide for common issues"

"Document the architecture and design decisions"
```

</v-click>

</div>

</div>

<div class="mt-8 p-6 bg-green-50 rounded-lg border-l-4 border-green-500">
  <strong>🎯 Goal:</strong> Transform an undocumented project into professional, well-documented code
</div>

<div class="mt-4 p-4 bg-indigo-100 rounded-lg border-l-4 border-indigo-500">
  <strong>⭐ Pro Tip:</strong> Ask Claude to follow your organization's documentation standards or create a CLAUDE.md file with documentation guidelines
</div>

---
layout: default
---

# Debugging Workflows

<div class="grid grid-cols-2 gap-8">

<div>

## Debugging Capabilities

<v-clicks>

- **Error message analysis** - Explain complex exceptions
- **Stack trace navigation** - Follow execution paths
- **Configuration debugging** - Spring Boot property issues
- **Integration debugging** - Service communication problems

</v-clicks>

</div>

<div>

<v-click>

### Example: Spring AI Debugging

```bash
# Common debugging scenarios:
"Explain this Spring AI configuration error"

"Why is my ChatClient not autowiring correctly?"

"Debug this API key authentication issue"

"Trace the execution flow for this failing test"
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-orange-100 rounded-lg border-l-4 border-orange-500">
  <strong>🛠️ Data Infrastructure Team:</strong> Used screenshots of dashboards to diagnose Kubernetes cluster issues, with Claude providing exact commands to fix pod IP address exhaustion
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Understanding the Interface

## Command Mode
<v-clicks>

- Interactive chat interface
- Context-aware responses
- File system access
- Git integration

</v-clicks>

## Auto-Accept Mode
<v-clicks>

- Press `Shift+Tab`
- Autonomous execution
- Minimal supervision
- Great for prototyping

</v-clicks>

## Plan Mode
<v-clicks>

- Press `Shift+Tab+Tab`
- Review implementation plans first
- Approve before execution
- Perfect for complex changes

</v-clicks>

::right::

## Key Features

<v-clicks>

- **Project memory** - Remembers context
- **File awareness** - Knows your codebase
- **Smart suggestions** - Contextual recommendations
- **Error handling** - Explains and fixes issues

</v-clicks>

<div class="mt-8 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>📝 From Anthropic teams:</strong> "Claude Code becomes a primary tool, open 80% of the time alongside your IDE"
</div>

---
layout: default
---

# Plan Mode: Review Before Execute

## Strategic Implementation Planning

<div class="grid grid-cols-2 gap-8">

<div>

### How to Activate

<v-clicks>

- **Press `Shift+Tab+Tab`** in any conversation
- Claude presents implementation plan
- **Review the strategy** before any code changes
- **Approve or modify** the approach
- **Execute with confidence**

</v-clicks>

</div>

<div>

<v-click>

### Perfect For

- **Complex refactoring** across multiple files
- **Architecture changes** requiring coordination
- **Security-sensitive** modifications  
- **Learning scenarios** where you want to understand the approach
- **Team reviews** of implementation strategies

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>🚀 NEW FEATURE:</strong> Plan Mode bridges autonomous execution and manual oversight - perfect for enterprise development
</div>

---
layout: default
---

# Headless Mode

Non-interactive execution

```bash
claude -p "update the README" with the latest changes"
```

- Use `-p` or `--print`
- Make sure `ANTHROPIC_API_KEY` is set

---
layout: default
---

# Other Helpful Flags

- Use `-c` or `--continue` to continue a conversation
- `--allowed-tools` does what it sounds like, as does `--disallowed-tools`
- `--model` to change between Sonnet or Opus
- `claude mcp` configures MCP servers
- `claude update` to update to the latest version

---
layout: default
---

# Memory and Context Management

## CLAUDE.md Files

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Project-specific instructions** - Guide Claude's behavior
- **Coding standards** - Enforce team conventions
- **Architecture decisions** - Document design patterns
- **Testing preferences** - Specify test frameworks and styles

</v-clicks>

</div>

<div>

<v-click>

### Example CLAUDE.md

```markdown
# Project Guidelines

## Code Style
- Use Java 21 features where appropriate
- Prefer records over traditional classes
- Use virtual threads for I/O operations

## Testing
- Write unit tests with JUnit 5
- Use Mockito for mocking
- Aim for 80%+ code coverage

## Documentation
- Update README for any new features
- Include API documentation
```

</v-click>

</div>

</div>

---
layout: default
---

# Project Memory with CLAUDE.md

## Persistent Context Across Sessions

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Automatically loaded** - Claude reads CLAUDE.md on startup
- **Session persistence** - Information carries between runs
- **Team knowledge** - Share project context with teammates
- **Living documentation** - Update as project evolves

</v-clicks>

</div>

<div>

<v-click>

### What to Include

```markdown
# Project Context

## Current Work
- Working on user authentication system
- Using Spring Security 6.x
- Database: PostgreSQL with JPA

## Recent Decisions
- Chose JWT tokens over sessions
- Using BCrypt for password hashing
- Repository pattern for data access

## Known Issues
- Performance bottleneck in UserService.findAll()
- Need to add rate limiting to login endpoint

## Next Steps
- Implement OAuth2 integration
- Add comprehensive integration tests
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>🧠 Key Benefit:</strong> Claude remembers your project context, decisions, and current work without having to re-explain everything
</div>

---
layout: default
---

# Mastering CLAUDE.md: Your AI Assistant's Knowledge Base

## Creating Effective Project Guidelines

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Bash commands** - Document project-specific scripts and tools
- **Code style guidelines** - Enforce team conventions automatically
- **Testing preferences** - Specify frameworks, patterns, and coverage goals
- **Architecture decisions** - Record design patterns and rationale

</v-clicks>

</div>

<div>

<v-click>

### Example CLAUDE.md

```markdown
# Project Development Guide

## Build Commands
- `./gradlew build` - Full build with tests
- `./gradlew bootRun` - Start development server

## Code Standards
- Use Java 21 records for data classes
- Prefer constructor injection in Spring
- Write tests with @SpringBootTest for integration

## Current Architecture
- Clean Architecture pattern
- Repository pattern for data access

## Known Issues
- UserService.findAll() has N+1 query problem
- Need to migrate from deprecated @RequestMapping
```

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>🧠 Pro Tip:</strong> Update CLAUDE.md as your project evolves - it becomes your team's institutional memory
</div>

---
layout: default
---

# Advanced CLI Features

## Conversation Management

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Continue conversations** with `-c` flag
- **Model selection** with `--model` flag
- **Tool control** with `--allowed-tools` and `--disallowed-tools`
- **Update Claude Code** with `claude update`

</v-clicks>

</div>

<div>

<v-click>

### Practical Examples

```bash
# Continue previous conversation
claude -c

# Use a specific model
claude --model claude-3-opus-20240229

# Restrict tools for security
claude --disallowed-tools bash

# Update to latest version
claude update
```

</v-click>

</div>

</div>

<div class="mt-6 p-3 bg-purple-100 rounded-lg border-l-4 border-purple-500 text-sm">
  <strong>🔧 Pro Tip:</strong> Use conversation continuity for complex, multi-step development tasks
</div>

---
layout: default
---

# Working with Images

## Visual Debugging and Analysis

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Screenshot analysis** - Paste error dialogs and stack traces
- **UI debugging** - Analyze interface issues
- **Chart interpretation** - Understand dashboards and metrics
- **Documentation** - Process architectural diagrams

</v-clicks>

</div>

<div>

<v-click>

### How to Use

```bash
# Take a screenshot of an error
# Copy to clipboard (Cmd+Shift+4 then Space)

# In Claude Code terminal:
# Paste the image with Ctrl+V (Mac/Windows/Linux)
# Note: Ctrl+V works better than Cmd+V on Mac

"Explain this error and suggest a fix"
```

</v-click>

</div>

</div>

<v-click>

<div class="mt-4 p-4 bg-gradient-to-r from-orange-50 to-red-50 rounded-lg border-l-4 border-orange-500">

**Data Infrastructure Team:** Used dashboard screenshots to diagnose Kubernetes cluster issues and received exact commands to fix pod IP exhaustion - **reduced debugging time from hours to minutes**

</div>

</v-click>

<div class="mt-4 p-3 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>💡 Pro Tip:</strong> Screenshots work great for error dialogs, browser developer tools, and IDE error panels
</div>

---
layout: default
---

# Enhance Communication with Visual References

## Using Screenshots and Mockups to Improve Claude's Understanding

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Error screenshots** - Paste IDE errors, browser console messages
- **UI mockups** - Share design sketches, wireframes, prototypes
- **Dashboard screenshots** - Debug system metrics and monitoring
- **Architectural diagrams** - Upload system design drawings

</v-clicks>

</div>

<div>

<v-click>

### Enhanced Workflow Examples

```bash
# Screenshot-driven debugging:
# 1. Take screenshot of error (Cmd+Shift+4)
# 2. Paste into Claude Code (Ctrl+V)
# 3. Ask for analysis

"Analyze this Spring Boot error and suggest a fix"

# UI implementation from mockup:
# 1. Share design mockup
# 2. Get implementation guidance

"Create a React component matching this design"

# Dashboard analysis:
# 1. Screenshot monitoring dashboard
# 2. Get diagnostic assistance

"What does this Kubernetes dashboard tell us about the pod issues?"
```

</v-click>

</div>

</div>

<v-click>

<div class="mt-8 p-6 bg-gradient-to-r from-orange-50 to-red-50 rounded-lg border-l-4 border-orange-500">

**🔍 Data Infrastructure Team Example:** Used dashboard screenshots to identify and resolve Kubernetes cluster issues in minutes instead of hours - Claude provided exact commands to fix pod IP exhaustion after analyzing visual metrics

</div>

</v-click>

<div class="mt-4 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>🎯 Key Principle:</strong> "A picture is worth a thousand words" - Visual context dramatically improves Claude's problem-solving accuracy
</div>

---
layout: default
---

# Advanced Features

<div class="grid grid-cols-2 gap-8">

<div>

## Extended Thinking Mode

<v-clicks>

- **Complex problem solving** - Multi-step reasoning
- **Architecture decisions** - Design pattern selection
- **Performance optimization** - Code improvement strategies

</v-clicks>

</div>

<div>

<v-click>

### Project Memory Setup

```bash
# Create Claude.md in your project root
echo "# Project Guidelines
- Use Spring Boot 3.x conventions
- Follow Java 21 patterns
- Prefer records over classes
- Use virtual threads for I/O
- Write comprehensive tests" > Claude.md
```

</v-click>

</div>

</div>

<v-click>

## Custom Slash Commands

<div class="mt-6 p-6 bg-gradient-to-r from-purple-50 to-pink-50 rounded-lg border-l-4 border-purple-500">

**🔧 Security Engineering:** Uses **50%** of all custom slash command implementations across the monorepo for streamlined workflows

</div>

</v-click>

---
layout: default
---

# Supercharge Claude with Custom Bash Scripts

## Integrating Powerful Automation

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Project-specific tools** - Custom build scripts, deployment helpers
- **Development workflows** - Automated testing, linting, formatting
- **Environment management** - Database setup, service orchestration
- **Code analysis** - Custom metrics, quality checks, dependency audits

</v-clicks>

</div>

<div>

<v-click>

### Example Integration Scripts

```bash
#!/bin/bash
# project-setup.sh - Environment initialization

echo "Setting up Spring Boot development environment..."

# Start required services
docker-compose -f docker/dev-compose.yml up -d

# Install dependencies and build
./gradlew clean build -x test

# Run database migrations
./gradlew flywayMigrate

# Generate test data
./gradlew loadTestData

echo "Development environment ready!"
echo "Run './gradlew bootRun' to start the application"
```

</v-click>

</div>

</div>

---
layout: default
---

# Claude Code Integration with Custom Scripts

## Putting Your Automation to Work

<div class="grid grid-cols-2 gap-8">

<div>

### Benefits

- **Seamless execution** - Claude runs your scripts directly
- **Contextual understanding** - Explains what each script does
- **Error handling** - Helps debug script failures
- **Workflow automation** - Chains multiple scripts together
- **Documentation integration** - Works with your CLAUDE.md files
- **Team consistency** - Standardized automation across projects

</div>

<div>

### Example Commands

```bash
"Run the project setup script"

"Use our deployment script for staging"

"Run the test suite with coverage"
```

**Common Use Cases:**
- Environment setup automation
- Deployment pipeline execution
- Testing and quality checks

</div>

</div>

<div class="mt-8 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>🔧 Pro Tip:</strong> Document your scripts in CLAUDE.md so Claude knows when and how to use them effectively
</div>

---
layout: default
---

# Custom Slash Commands

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Automate repetitive tasks** - Package common workflows
- **Team standardization** - Share commands across projects
- **Domain-specific actions** - Create commands for your tech stack
- **Quick shortcuts** - Access complex operations instantly

</v-clicks>

</div>

<div>

<v-click>

### Creating a Slash Command

```bash
# Create .claude/slash_commands directory
mkdir -p .claude/slash_commands

# Create a command file
touch .claude/slash_commands/spring-service.md
```

```markdown
# Create Spring Service

Create a new Spring Boot service class named $ARGUMENTS with:
- @Service annotation
- Constructor injection for $ARGUMENTS repository
- Basic CRUD operations for $ARGUMENTS entity
- Comprehensive logging
- Exception handling
- Unit tests with @MockBean

Use modern Java features and follow Spring best practices.
```

**Usage:** `/spring-service User` creates a UserService class

</v-click>

</div>

</div>

---
layout: default
---

# Slash Command Examples

## Practical Commands for Java/Spring Development

<div class="grid grid-cols-2 gap-8">

<div>

### `/spring-controller`

<v-click>

```markdown
# Create Spring REST Controller

Generate a $ARGUMENTS REST controller with:
- @RestController and @RequestMapping("/$ARGUMENTS")
- CRUD endpoints (GET, POST, PUT, DELETE)
- Proper HTTP status codes
- Request/response DTOs for $ARGUMENTS
- Validation annotations
- OpenAPI documentation
- Integration tests

**Usage:** `/spring-controller users` creates UsersController
```

</v-click>

</div>

<div>

### `/modernize-java`

<v-click>

```markdown
# Modernize Java Code

Update the selected code to use:
- Records instead of traditional classes
- Switch expressions
- Pattern matching where applicable
- Virtual threads for I/O operations
- Modern collection methods
- Text blocks for multiline strings
- Sealed classes if appropriate
```

</v-click>

</div>

</div>

---
layout: default
---

# Security-Focused Slash Commands

## Code Review and Security Analysis

<div class="grid grid-cols-2 gap-8">

<div>

### `/review-security`

```markdown
# Security Code Review

Review code for security issues:
- SQL injection vulnerabilities
- XSS prevention
- Authentication/authorization flaws
- Input validation gaps
- Sensitive data exposure
- Insecure cryptography
```

</div>

<div>

### `/security-audit`

```markdown
# Security Audit

Perform comprehensive security analysis on $ARGUMENTS:
- Authentication mechanisms
- Authorization controls  
- Data encryption practices
- API security patterns
- Dependency vulnerabilities
- Configuration security
```

**Usage:** `/security-audit UserController` audits specific class

</div>

</div>

<div class="mt-8 p-4 bg-red-100 rounded-lg border-l-4 border-red-500">
  <strong>🔒 Security Focus:</strong> Use these commands regularly during code reviews and before production deployments
</div>

---
layout: default
---

# Advanced Slash Commands

## Team-Specific Workflows

<div class="grid grid-cols-2 gap-8">

<div>

### Organization-Wide Commands

<v-clicks>

- **Code review templates** - Standardized review processes
- **Deployment scripts** - Environment-specific deployments
- **Testing patterns** - Consistent test structures
- **Documentation formats** - Company documentation standards

</v-clicks>

</div>

<div>

<v-click>

### Command Best Practices

```markdown
# Structure Tips

## Instructions
- Be specific about requirements
- Include tech preferences
- Specify coding standards

## Context
- Reference project patterns
- Include naming conventions

## Quality
- Always include tests
- Add error handling
```

</v-click>

</div>

</div>

<div class="mt-4 p-3 bg-purple-100 rounded-lg border-l-4 border-purple-500 text-sm">
  <strong>🔧 Security Engineering:</strong> Uses 50% of all custom slash commands across monorepo
</div>

---
layout: default
---

# Claude Code SDKs: Programmatic Integration

## Building Custom AI-Powered Development Tools

<div class="grid grid-cols-2 gap-8">

<div>

### Available SDKs

<v-clicks>

- **TypeScript SDK** - Node.js and web apps
- **Python SDK** - Data science and automation
- **CLI integration** - Subprocess scripting
- **Cross-platform** - Windows, macOS, Linux

</v-clicks>

</div>

<div>

<v-click>

### Key Capabilities

- **Multi-turn conversations** - Maintain context
- **Custom system prompts** - Define AI behavior
- **MCP integration** - Connect external tools
- **Streaming responses** - Real-time output
- **Tool permissions** - Fine-grained control

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-purple-100 rounded-lg border-l-4 border-purple-500 text-sm">
  <strong>🚀 SDK Power:</strong> Transform Claude Code from CLI tool into programmable AI assistant for custom workflows
</div>

---
layout: default
---

# Advanced Automation: Beyond Code

## Dynamic Documentation and Presentation Generation

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Auto-generated onboarding** - Convert codebase analysis to presentations
- **Scripted reporting workflows** - Automated git analysis and summaries  
- **Multi-modal outputs** - Text to slides, speech, documentation
- **Team standardization** - Consistent onboarding across projects

</v-clicks>

</div>

<div>

<v-click>

### Slidev Integration Example

```bash
# Create dynamic onboarding slash command
# .claude/slash_commands/onboard.md

# Codebase Onboarding Generator
1. Analyze project structure and key components
2. Write findings to CODEBASE.md with architecture overview
3. Convert analysis to PRESENTATION.md using Slidev format
4. Include: setup instructions, key patterns, gotchas
5. Run: npm run dev to view presentation

Use professional tone, focus on practical insights.
```

</v-click>

</div>

</div>

---
layout: default
---

# Automated Reporting with Claude Code

## Weekly Summaries and Project Analysis

<div class="grid grid-cols-2 gap-8">

<div>

### Automated Weekly Reports

```bash
#!/bin/bash
# weekly_summary.sh - Project analysis

claude -p "Analyze last week's git changes. 
Focus on most edited files, new features, 
and technical decisions. Write results 
to weekly_report.md as a narrative." \
--allowedTools "Bash(git log:*)" \
"Bash(git diff:*)" "Write"

# Optional: Convert to presentation
# slidev build weekly_report.md
```

</div>

<div>

### Other Automation Ideas

- **Sprint retrospectives** - Analyze completed work and blockers
- **Code quality reports** - Track technical debt and improvements  
- **Dependency audits** - Monitor library updates and vulnerabilities
- **Performance tracking** - Analyze build times and test execution
- **Team productivity** - Summarize commits, PRs, and code reviews
- **Documentation updates** - Auto-generate changelog entries

</div>

</div>

<div class="mt-6 p-3 bg-gradient-to-r from-yellow-50 to-blue-50 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>⚠️ Security:</strong> Use specific `--allowedTools` instead of dangerous permissions | <strong>💰 Cost:</strong> Test on smaller projects first - large codebases consume significant tokens
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Model Context Protocol (MCP)

## What is MCP?

<v-clicks>

- **Standard protocol** - Connect AI to external systems
- **Tool integration** - Access APIs, databases, services
- **Context enhancement** - Provide relevant data to AI
- **Security controls** - Manage access and permissions

</v-clicks>

::right::

## Your MCP Server Examples

<div class="space-y-4">

<v-click>

### GitHub MCP Server
- Repository operations
- Issue management
- Pull request handling
- File content access

</v-click>

<v-click>

### Osquery MCP Server
- System diagnostics
- Process monitoring
- Network analysis
- Security insights

</v-click>

</div>

<div class="mt-4 p-3 bg-red-100 rounded-lg border-l-4 border-red-500 text-sm">
  <strong>🔒 Security Note:</strong> Use MCP servers instead of CLI for sensitive data
</div>

---
layout: default
---

# Setting Up MCP Servers

## Local and Remote Configuration Options

<div class="grid grid-cols-2 gap-8">

<div>

### Local MCP Servers

<v-clicks>

- **`claude mcp`** - Interactive local setup
- **Self-hosted control** - Full configuration access
- **Custom implementations** - Build your own servers
- **Development testing** - Perfect for experimentation

</v-clicks>

</div>

<div>

### Remote MCP Servers

<v-clicks>

- **Cloud-hosted services** - Vendor-managed infrastructure
- **OAuth authentication** - Enterprise-secure connections
- **Zero maintenance** - No updates or scaling needed
- **SaaS integrations** - Direct tool connections

</v-clicks>

</div>

</div>

<v-click>

### Setup Examples

```bash
# Local setup
claude mcp  # Configure local servers

# Remote services (OAuth-enabled)
# Connect to Sentry, Linear, GitHub Enterprise
# Authentication handled via secure OAuth flow
# No local server management required
```

</v-click>

<div class="mt-6 p-4 bg-green-100 rounded-lg border-l-4 border-green-500 text-sm">
  <strong>🚀 NEW:</strong> Remote MCP servers eliminate local setup complexity while providing enterprise-grade security
</div>

---
layout: default
---

# Available MCP Servers

## Local and Remote Server Options

<div class="grid grid-cols-2 gap-8">

<div>

### Development Tools

<v-clicks>

- **GitHub** - Repository management, issues, PRs
- **Sentry** - Error tracking and debugging context
- **Linear** - Project management and issue tracking
- **File System** - Enhanced local file operations
- **Database** - Query and schema operations

</v-clicks>

</div>

<div>

### Enterprise & SaaS

<v-clicks>

- **Slack** - Team communication integration
- **Google Drive** - Document access
- **Notion** - Knowledge base integration
- **Docker** - Container management
- **Kubernetes** - Cluster operations

</v-clicks>

</div>

</div>

<v-click>

## Security & Authentication

<div class="mt-6 grid grid-cols-2 gap-6">

<div class="p-4 bg-green-50 rounded-lg border-l-4 border-green-500">
<strong>OAuth Integration</strong><br>
Secure enterprise authentication for remote servers
</div>

<div class="p-4 bg-blue-50 rounded-lg border-l-4 border-blue-500">
<strong>Vendor-Managed</strong><br>
Zero-maintenance remote infrastructure
</div>

</div>

</v-click>

---
layout: default
---

# MCP in Practice

## Real-World Workflows with Remote Integration

<div class="grid grid-cols-2 gap-8">

<div>

### Enhanced Development Workflow

<v-clicks>

1. **Error tracking** via Sentry MCP integration
2. **Issue management** through Linear MCP
3. **Code analysis** with GitHub MCP
4. **Team coordination** via Slack MCP
5. **Documentation sync** across all tools

</v-clicks>

</div>

<div>

<v-click>

### Example Commands

```bash
# Using Linear MCP
"Show me high-priority issues assigned to my team
and create a work plan"

# Using Sentry MCP  
"Analyze recent errors in production
and suggest fixes based on stack traces"

# Using GitHub MCP
"Review this PR and check if it addresses
the Linear issue requirements"
```

</v-click>

</div>

</div>

<v-click>

<div class="mt-6 p-4 bg-gradient-to-r from-blue-50 to-purple-50 rounded-lg border-l-4 border-blue-500">
<strong>💡 Linear Example:</strong> "Linear's MCP integration brings Linear projects and issues directly into Claude Code... Fewer tabs, less copy-paste. Better software, faster." - Tom Moor, Linear
</div>

</v-click>

<div class="mt-4 p-4 bg-green-100 rounded-lg border-l-4 border-green-500">
  <strong>🚀 Impact:</strong> Remote MCP transforms Claude Code into a unified development hub that eliminates context switching
</div>

---
layout: default
---

# Practice Projects

## Public GitHub Repositories for Experimentation

<div class="grid grid-cols-2 gap-8">

<div>

### 🔍 Analysis Example
**Flask Example** - *See Claude Code's analysis in action*

<v-click>

**Repository:** https://github.com/XD-DENG/flask-example

**Great for:**
- Quick issue identification
- Security problem detection
- Code quality analysis
- Best practice validation

**Perfect for:** Seeing Claude Code analysis in action

</v-click>

</div>

<div>

### 🌱 Beginner Project
**Python Weather App** - *Solid foundation with room for growth*

<v-click>

**Repository:** https://github.com/rachanahegde/python-weather-app

**Great for:**
- Clear structure
- Working functionality
- Room for improvements
- Beginner-friendly

**Perfect for:** Adding tests, docs, modern Python

</v-click>

</div>

</div>

<v-click>

### 🌐 API Testing Resource
**JSONPlaceholder** - *Free REST API for testing*

**URL:** https://jsonplaceholder.typicode.com/

**Great for:**
- Building API clients
- Integration testing
- Error handling
- Async operations

**Perfect for:** API client generation and HTTP request handling

</v-click>

<div class="mt-6 p-3 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>💡 Exercise Ideas:</strong> Clone for analysis, build API clients, add tests, improve docs
</div>

---
layout: default
---

# Ken's Projects for Practice

<div class="grid grid-cols-3 gap-6 mt-6">

<div>

### 🎵 Lyrics Trainer
<p class="text-sm">JavaScript/TypeScript Web App</p>

<v-click>

**Repo:** kousen/lyrics_trainer

**Tech:**
- Modern JS/TypeScript
- Web APIs & DOM
- Client-side architecture

**Practice:** Frontend dev, API integration

</v-click>

</div>

<div>

### 📜 Certificate Service
<p class="text-sm">Spring Boot PDF Generator</p>

<v-click>

**Repo:** kousen/certificate-service

**Tech:**
- Spring Boot
- PDF generation
- Heroku deployment

**Practice:** Backend services, cloud deployment

</v-click>

</div>

<div>

### 🛒 Shopping Service
<p class="text-sm">Spring Boot RESTful Teaching App</p>

<v-click>

**Repo:** kousen/shopping_v3

**Tech:**
- Spring Boot 3.x
- RESTful architecture
- Teaching-focused

**Practice:** REST APIs, Spring patterns

</v-click>

</div>

</div>

<div class="mt-6 p-3 bg-green-100 rounded-lg border-l-4 border-green-500 text-sm">
  <strong>🎯 Advantage:</strong> These are Ken's real projects - ask him about architecture decisions during training!
</div>

---
layout: default
---

# Advanced: Multi-Claude Parallel Workflows

## Scaling Development with Parallel AI Assistance

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Git worktrees** - Multiple Claude instances on different branches
- **Parallel feature development** - Simultaneous work on independent features
- **Team coordination** - Shared Claude.md files and conventions
- **Distributed debugging** - Multiple Claude instances analyzing different system components

</v-clicks>

</div>

<div>

<v-click>

### Practical Implementation

```bash
# Setup parallel workspaces
git worktree add ../project-feature-auth feature/oauth2
git worktree add ../project-feature-api feature/api-v2
git worktree add ../project-hotfix hotfix/security-patch

# Terminal 1: OAuth2 feature
cd ../project-feature-auth
claude "Implement OAuth2 integration with Spring Security"

# Terminal 2: API development
cd ../project-feature-api
claude "Design and implement REST API v2 with OpenAPI docs"

# Terminal 3: Security hotfix
cd ../project-hotfix
claude "Fix the authentication bypass vulnerability"
```

</v-click>

</div>

</div>

<v-click>

<div class="mt-8 p-6 bg-gradient-to-r from-purple-50 to-blue-50 rounded-lg border-l-4 border-purple-500">

**🔧 Advanced Team Strategy:**
- **Shared CLAUDE.md** templates ensure consistency across all parallel work
- **Branch-specific instructions** guide Claude toward feature-appropriate solutions
- **Merge coordination** with Claude helping resolve conflicts between parallel streams
- **Quality gates** where Claude reviews and validates integration points

</div>

</v-click>

<div class="mt-4 p-3 bg-yellow-100 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>⚠️ Resource Note:</strong> Multiple Claude instances consume rate limits faster - consider higher-tier plans
</div>

---
layout: default
---

# Hands-On Exercise Overview

<div class="grid grid-cols-2 gap-12 mt-8">

<div>

## Refactoring Legacy Code

<v-clicks>

- Modernize Java syntax
- Update Spring configurations
- Improve error handling
- Add comprehensive tests

</v-clicks>

</div>

<div>

## Documentation Creation

<v-clicks>

- Generate README files
- Create API documentation
- Add inline comments
- Write setup guides

</v-clicks>

</div>

</div>

<v-click>

<div class="mt-12 p-6 bg-gradient-to-r from-blue-50 to-purple-50 rounded-lg border-2 border-dashed border-blue-300">
  <h3 class="text-xl font-bold text-blue-800">🚀 Coming Up: Live Exercises</h3>
  <p class="text-blue-600 mt-2">We'll work through real examples from Spring AI and MCP projects</p>
</div>

</v-click>

---
layout: default
---

# Exercise 1: Legacy Code Refactoring

## Scenario
You have a Spring Boot service using older Java patterns. Use Claude Code to modernize it.

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

## Tasks

<v-clicks>

1. **Convert classes to records** where appropriate
2. **Add virtual thread support** for I/O operations
3. **Update to modern Spring patterns**
4. **Add comprehensive error handling**
5. **Generate missing tests**

</v-clicks>

</div>

<div>

<v-click>

### Example Starting Point

```java
public class UserService {
    private final UserRepository repository;
    
    public UserService(UserRepository repository) {
        this.repository = repository;
    }
    
    public User findUser(String id) {
        return repository.findById(id).orElse(null);
    }
}
```

</v-click>

</div>

</div>

<div class="mt-6 flex justify-center">
  <div class="px-6 py-3 bg-blue-500 text-white rounded-lg font-semibold">
    ⏱️ Time: 15 minutes | 🎯 Goal: Modernize the service class completely
  </div>
</div>

---
layout: default
---

# Exercise 2: Documentation Generation

## Scenario
Create comprehensive documentation for an undocumented Spring AI integration.

<div class="grid grid-cols-2 gap-8 mt-6">

<div>

## Tasks

<v-clicks>

1. **Generate README.md** with setup instructions
2. **Create API documentation** for REST endpoints
3. **Add inline comments** to complex methods
4. **Write configuration guide** for environment variables

</v-clicks>

</div>

<div>

### Follow This Pattern

<v-click>

**From your GitHub MCP Server documentation:**

</v-click>

<v-clicks at="2">

- Clear overview and features
- Step-by-step setup guide
- Configuration examples
- Usage examples with code
- Troubleshooting section

</v-clicks>

</div>

</div>

<div class="mt-6 flex justify-center">
  <div class="px-6 py-3 bg-green-500 text-white rounded-lg font-semibold">
    ⏱️ Time: 15 minutes | 🎯 Goal: Professional-quality documentation
  </div>
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Best Practices

## Effective Prompt Crafting

<v-clicks>

- **Be specific** - Clear, detailed instructions work better
- **Provide context** - Explain your goals and constraints
- **Iterate gradually** - Make incremental improvements
- **Use examples** - Show desired patterns or styles

</v-clicks>

::right::

<div class="space-y-6">

<div>

### Development Process

<v-clicks>

- Start with clean git state
- Commit checkpoints regularly
- Review changes before accepting
- Test generated code thoroughly

</v-clicks>

</div>

<div>

### Team Collaboration

<v-clicks>

- Share Claude.md configurations
- Document successful patterns
- Review AI-generated code together
- Establish team conventions

</v-clicks>

</div>

</div>

<div class="mt-8 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>🔑 Key Insight:</strong> Treat Claude Code as an iterative partner, not a one-shot solution
</div>

---
layout: two-cols
layoutClass: gap-16
---

# Maintaining Control

## Three Levels of AI Autonomy

### Supervised Mode (Default)

<v-clicks>

- Review each change individually
- Core business logic
- Security-critical code
- Learning and exploration

</v-clicks>

### Plan Mode (`Shift+Tab+Tab`)

<v-clicks>

- Review implementation plans first
- Complex multi-file changes
- Architecture modifications
- Strategic refactoring

</v-clicks>

### Auto-Accept Mode (`Shift+Tab`)

<v-clicks>

- Minimal supervision
- Prototyping and experimentation
- Documentation and tests
- Routine tasks

</v-clicks>

::right::

<v-click>

## Checkpoint Strategy

<div class="p-6 bg-gradient-to-r from-green-50 to-blue-50 rounded-lg border-l-4 border-green-500">

**RL Engineering Approach:**
- 📝 Frequently commit checkpoints during Claude's work
- 🔄 Use "try and rollback" methodology
- 🧪 Enable experimental approach without risk

</div>

</v-click>

<div class="mt-4 p-3 bg-blue-100 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>🚀 NEW Plan Mode:</strong> Use `Shift+Tab+Tab` to review implementation strategies before execution - perfect for complex changes
</div>

<div class="mt-3 p-3 bg-yellow-100 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>📊 Rule of Thumb:</strong> Claude works on first attempt about one-third of the time - plan accordingly
</div>

---
layout: default
---

# The Power of Iteration

## Mastering the Iterative Development Process

<div class="grid grid-cols-2 gap-8">

<div>

<v-clicks>

- **Start with broad questions** - Get the big picture first
- **Refine incrementally** - Add details and constraints progressively  
- **Use visual references** - Screenshots, mockups, diagrams for clarity
- **Course-correct immediately** - Don't let Claude go down wrong paths

</v-clicks>

</div>

<div>

<v-click>

### Effective Iteration Examples

```bash
# Iteration 1: Broad exploration
"Analyze this Spring Boot application structure"

# Iteration 2: Focused investigation  
"Focus on the security configuration - what authentication method is used?"

# Iteration 3: Specific improvement
"Update the security config to use JWT tokens with proper validation"

# Iteration 4: Quality enhancement
"Add comprehensive tests for the JWT token validation logic"

# Iteration 5: Documentation
"Document the JWT implementation in the README and add setup instructions"
```

</v-click>

</div>

</div>

<v-click>

<div class="mt-8 p-6 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-lg border-l-4 border-blue-500">

**🔑 Key Insight:** "Claude performs best when it has a clear target to iterate against"

**Success Pattern:**
1. **Provide context** through visuals, examples, or detailed descriptions
2. **Guide progressively** with specific, actionable feedback
3. **Correct course early** when Claude heads in the wrong direction
4. **Build on successes** by iterating on what works well

</div>

</v-click>

<div class="mt-3 p-3 bg-yellow-100 rounded-lg border-l-4 border-yellow-500 text-sm">
  <strong>⚡ Pro Tip:</strong> Think of Claude as a collaborative partner - provide feedback like you would to a skilled teammate
</div>

---
layout: default
---

# Cost Optimization Strategies

<div class="grid grid-cols-2 gap-8">

<div>

## Efficient Usage Patterns

<v-clicks>

- **Batch similar tasks** - Group related operations
- **Use precise prompts** - Avoid unnecessary iterations
- **Leverage project memory** - Reduce context repetition
- **Start simple** - Begin with minimal viable requests

</v-clicks>

</div>

<div>

<v-click>

### High-Value Tasks
✅ Complex refactoring  
✅ Test generation  
✅ Documentation creation  
✅ Bug investigation

### Consider Alternatives
❌ Simple text editing  
❌ Basic file operations  
❌ Routine formatting  
❌ Simple grep operations

</v-click>

</div>

</div>

<div class="mt-8 p-4 bg-purple-100 rounded-lg border-l-4 border-purple-500">
  <strong>💡 Growth Marketing Insight:</strong> Focus on API-enabled repetitive tasks where Claude Code provides the most value
</div>

<v-click>

<div class="mt-6 p-6 bg-gradient-to-r from-green-50 to-blue-50 rounded-lg border-l-4 border-green-500">

**💰 Plan Optimization Tips:**

- **Pro Plan ($20):** Perfect for learning and small projects
- **Max 5x ($100):** Sweet spot for most professional developers  
- **Max 20x ($200):** Enterprise teams with large codebases
- **Sonnet vs Opus:** Use Sonnet 4 for most tasks (5x cheaper than Opus)
- **Rate Limit Timing:** Limits reset every 5 hours - plan intensive work accordingly

</div>

</v-click>

---
layout: default
---

# Good Practices

- Create a new branch before turning Claude Code loose
- Don't forget to ask it to update the README files
- Be sure to update CLAUDE.md as well
- Use `/compact` during natural breaks in development
- Add *think* or *think hard* or *think deeply* as necessary
- Use `--continue` or `--resume` to access previous conversations
- Note: if console scrolls past buffer, you lose visibility (not the actual conversation)
- Use console logging to save important outputs for reference

---
layout: default
---

# Future Developments

<div class="grid grid-cols-2 gap-8">

<div>

## Emerging Capabilities

<v-clicks>

- **Enhanced MCP integration** - More tool connections
- **Improved autonomous operation** - Longer independent work
- **Better error recovery** - Self-correction capabilities
- **IDE integration** - Deeper development environment integration

</v-clicks>

</div>

<div>

<v-click>

### Industry Trends

**Technical Evolution:**
- More sophisticated reasoning
- Better code understanding
- Enhanced multi-language support
- Improved testing capabilities

**Workflow Integration:**
- CI/CD pipeline integration
- Code review automation
- Security scanning integration
- Performance optimization

</v-click>

</div>

</div>

<div class="mt-6 p-4 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-lg border-l-4 border-blue-500 text-sm">
  <strong>🚀 Vision:</strong> Claude Code as a fundamental part of the development lifecycle, not just a helper tool
</div>

---
layout: default
---

# Real-World Success Stories

<div class="grid grid-cols-2 gap-6">

<div>

### Product Development
<v-clicks>

- **70% code autonomy** for Vim mode implementation
- **Faster prototyping** with auto-accept mode
- **Quality maintenance** through automated testing

</v-clicks>

### Data Science
<v-clicks>

- **5,000-line TypeScript apps** built with minimal JS knowledge
- **2-4x time savings** on routine refactoring
- **Persistent tools** instead of throwaway notebooks

</v-clicks>

</div>

<div>

### Security Engineering
<v-clicks>

- **50% reduction** in incident resolution time
- **Days to weeks** improvement in project onboarding
- **Autonomous documentation** synthesis

</v-clicks>

### Growth Marketing
<v-clicks>

- **2 hours to 15 minutes** for ad copy creation
- **10x increase** in creative output
- **Team-level productivity** with single-person team

</v-clicks>

</div>

</div>

---
layout: default
---

# Your Success Framework

## Getting Started Checklist

<v-clicks>

1. **Install and configure** Claude Code in your environment
2. **Create Claude.md** files for your key projects
3. **Start with low-risk tasks** like documentation and tests
4. **Build confidence** with supervised operations
5. **Graduate to autonomous** mode for appropriate tasks

</v-clicks>

<div class="mt-8 text-sm text-gray-600">
  💡 <strong>Remember:</strong> Share prototypes and workflows with your team to multiply the impact
</div>

---
layout: default
---

# Progressive Adoption Strategy

<div class="mt-8 p-6 bg-gradient-to-r from-green-50 to-blue-50 rounded-lg">

<v-clicks>

- **Week 1:** Basic code exploration and documentation  
- **Week 2:** Test generation and simple refactoring  
- **Week 3:** Complex debugging and multi-file operations  
- **Week 4:** Autonomous development workflows

</v-clicks>

</div>

<v-click>

<div class="mt-8 p-4 bg-yellow-100 rounded-lg border-l-4 border-yellow-500">
  <strong>🚀 Pro Tip:</strong> Start with small wins to build confidence and demonstrate value to your team
</div>

</v-click>

---
layout: two-cols
layoutClass: gap-16
---

# Key Takeaways

## Transform Your Development Process

<v-clicks>

- **Code understanding** - Navigate complex codebases effortlessly
- **Quality assurance** - Generate comprehensive tests automatically
- **Documentation** - Create professional docs in minutes
- **Debugging** - Resolve issues faster with AI assistance
- **Modernization** - Refactor legacy code to modern patterns

</v-clicks>

::right::

<div class="space-y-6">

<div>

### Technical Excellence

<v-clicks>

- Precise, detailed prompts
- Iterative collaboration
- Checkpoint-driven development
- Context-aware workflows

</v-clicks>

</div>

<div>

### Strategic Integration

<v-clicks>

- Team knowledge sharing
- Progressive complexity adoption
- Cost-conscious usage
- Continuous improvement

</v-clicks>

</div>

</div>

<div class="mt-8 p-6 bg-gradient-to-r from-purple-50 to-pink-50 rounded-lg border-l-4 border-purple-500 text-center">
  <strong class="text-lg">🚀 Claude Code isn't just a tool - it's a development force multiplier</strong>
</div>

---
layout: default
---

# Contact Info & Resources

<div class="grid grid-cols-2 gap-12 items-start text-left">

<div>

**Ken Kousen**  
Kousen IT, Inc.

ken.kousen@kousenit.com  
http://www.kousenit.com  
https://kousenit.org (blog)  
<a href="https://twitter.com/kenkousen" target="_blank">@kenkousen</a> (twitter)  
https://foojay.social/@kenkousen (mastodon)  
https://bsky.app/profile/kousenit.com (bluesky)  

*Tales from the jar side* (free newsletter)  
https://kenkousen.substack.com  
https://youtube.com/@talesfromthejarside

</div>

<div>

**Books by Ken Kousen:**

<div class="mt-4 space-y-2">
<div><a href="https://pragprog.com/titles/kkmanage/help-your-boss-help-you/" target="_blank">📚 Help Your Boss Help You</a></div>
<div><a href="https://www.amazon.com/Kotlin-Cookbook-Problem-Focused-Ken-Kousen/dp/1492046671" target="_blank">📚 Kotlin Cookbook</a></div>
<div><a href="https://www.amazon.com/Modern-Java-Recipes-Solutions-Difficult/dp/149197317X" target="_blank">📚 Modern Java Recipes</a></div>
<div><a href="https://www.manning.com/books/making-java-groovy" target="_blank">📚 Making Java Groovy</a></div>
<div><a href="https://www.amazon.com/Gradle-Recipes-Android-Master-System/dp/1491947020" target="_blank">📚 Gradle Recipes for Android</a></div>
<div><a href="https://pragprog.com/titles/mockito/mockito-made-clear/" target="_blank">📚 Mockito Made Clear</a></div>
</div>

</div>

</div>

---
layout: end
class: text-center
---

# Thank You!

## Questions & Discussion

<div class="mt-12 space-y-4">

**📚 Official Documentation:** [docs.anthropic.com](https://docs.anthropic.com/en/docs/claude-code/overview)

**🏆 Best Practices Guide:** [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices)

**🚀 Remote MCP Announcement:** [Claude Code Remote MCP](https://www.anthropic.com/news/claude-code-remote-mcp)

**⚙️ SDK Documentation:** [Claude Code SDKs](https://docs.anthropic.com/en/docs/claude-code/sdk)

**📧 Ken Kousen:** ken.kousen@kousenit.com

**🎓 Training Resources:** kousenit.com

</div>

<div class="mt-16 text-lg italic text-gray-600">
  Continue your Claude Code journey<br>
  Build amazing things with AI assistance
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://twitter.com/kenkousen" target="_blank" alt="Twitter"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-twitter />
  </a>
  <a href="https://github.com/kousen" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>