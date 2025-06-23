---
theme: seriph
background: https://source.unsplash.com/1920x1080/?coding,ai
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Claude Code Training Labs
  Hands-On Exercises for Professional Development Workshop
drawings:
  persist: false
transition: slide-left
title: Claude Code Training Labs
mdc: true
---

# Claude Code Training Labs
## Hands-On Exercises

**Ken Kousen**  
*Author • Speaker • Developer*

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Practice exercises to master Claude Code workflows <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: default
---

# Labs Overview

## Exercise Structure

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

### Progressive Learning
- **Lab 1**: First Steps (5 minutes)
- **Lab 2**: Code Exploration (10 minutes)  
- **Lab 3**: Test Generation (15 minutes)
- **Lab 4**: Documentation (15 minutes)
- **Lab 5**: Legacy Refactoring (15 minutes)
- **Lab 6**: Documentation Creation (15 minutes)

</div>

<div>

### Skills Developed
- Project exploration and understanding
- Comprehensive test suite creation
- Professional documentation generation
- Legacy code modernization
- Spring Boot refactoring patterns
- Real-world debugging scenarios

</div>

</div>

<div class="mt-8 p-4 bg-blue-100 rounded-lg border-l-4 border-blue-500">
  <strong>🎯 Goal:</strong> Build confidence with Claude Code through hands-on practice using real-world scenarios
</div>

---
layout: default
---

# Lab 1: First Steps with Claude Code

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

# Lab 2: Explore a Codebase

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

# Lab 3: Generate Tests

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
layout: default
---

# Lab 4: Create Documentation

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

# Lab 5: Legacy Code Refactoring

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

# Lab 6: Documentation Generation

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
layout: default
---