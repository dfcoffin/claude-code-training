# Claude Code Training Labs

This document contains hands-on exercises for learning to use Claude Code for professional development workflows.

## Table of Contents

0. [Lab 0: Project Creation from Scratch](#lab-0-project-creation-from-scratch)
1. [Lab 1: First Steps with Claude Code](#lab-1-first-steps-with-claude-code)
2. [Lab 2: Code Exploration](#lab-2-code-exploration)
3. [Lab 3: Test Generation](#lab-3-test-generation)
4. [Lab 4: Documentation Creation](#lab-4-documentation-creation)
5. [Lab 5: Legacy Code Refactoring](#lab-5-legacy-code-refactoring)
6. [Lab 6: Advanced Workflows](#lab-6-advanced-workflows)

## Prerequisites

- Claude Code installed and configured
- API key set in environment: `export ANTHROPIC_API_KEY="your-key"`
- Git repository access
- Development environment for multiple languages (Python, JavaScript/TypeScript, Java)

## Lab 0: Project Creation from Scratch

**Duration**: 20 minutes  
**Goal**: Create a lyrics display application from scratch (this is how the `lyrics-trainer` project began, which we'll look at later)

### Setup

1. Create a new empty directory: `mkdir lyrics-display && cd lyrics-display`
2. Initialize git: `git init`
3. Start Claude Code: `claude`
4. Create your first branch: `git checkout -b basic-lyrics-app`
5. Find song lyrics: Google any song title + "lyrics" and copy the lyrics to a text file called `lyrics.txt`

### Exercises

1. **Project foundation**:
   ```
   "I have song lyrics saved in lyrics.txt. Create a web application that displays these lyrics one line at a time with three buttons: Next, Previous, and Play. The Play button should automatically advance through lines with a 2-second delay."
   ```

2. **Enhanced functionality**:
   ```
   "Add line numbering, show progress (e.g., 'Line 5 of 32'), and make the Play button toggle to Pause when active. Style it to look modern and clean."
   ```

3. **Visual improvements**:
   ```
   "Add smooth transitions between lines, better typography, and responsive design. Make it visually appealing with a music-themed color scheme."
   ```

4. **Advanced features**:
   ```
   "Add keyboard shortcuts: spacebar for play/pause, arrow keys for next/previous. Also add a progress bar showing position in the song."
   ```

5. **Documentation and structure**:
   ```
   "Create a README.md explaining the project, and organize the code into separate CSS and JavaScript files for better maintainability."
   ```

6. **Version control and experimentation**:
   ```
   "Help me commit this work, then create a new branch called 'speed-control' and add a slider to control the playback speed."
   ```

### Expected Outcomes

- Build a real, useful application from nothing
- See how Claude Code handles file interactions and user interface logic
- Experience the full development cycle: concept → working app → enhancements
- Understand that this is exactly how the `lyrics-trainer` project started
- Practice iterative development with AI assistance

**Note**: This exercise recreates the origin story of the `lyrics-trainer` project in the exercises folder - you're experiencing the same process that created one of our example applications!

[← Back to Table of Contents](#table-of-contents)

## Lab 1: Claude Code on an Existing Project

**Duration**: 5 minutes  
**Goal**: Get comfortable with the basic Claude Code interface

### Setup

1. Navigate to any existing project directory
2. Start Claude Code: `claude`
3. Verify the interface responds to basic commands

### Exercises

1. **Basic interaction**: Ask Claude Code to explain what it can do
   ```
   "What are your main capabilities for helping with development?"
   ```

2. **Project overview**: Get a high-level understanding
   ```
   "Give me an overview of this project structure"
   ```

3. **File exploration**: Find specific files
   ```
   "Show me the main application files in this project"
   ```

### Expected Outcomes

- Understand Claude Code's conversational interface
- See how it analyzes project structure
- Practice natural language interaction

[← Back to Table of Contents](#table-of-contents)

## Lab 2: Code Exploration

**Duration**: 10 minutes  
**Goal**: Use Claude Code to understand a complex codebase

### Setup

Choose one of the provided exercise projects:
- `exercises/java/certificate-service` (Spring Boot PDF generation)
- `exercises/java/shopping-service` (Legacy Grails/Groovy application)
- `exercises/javascript/lyrics-trainer` (TypeScript web app)
- `exercises/python/weather-app` (Flask application)

### Exercises

1. **Architecture analysis**: 
   ```
   "Analyze the architecture of this application and explain the main components"
   ```

2. **Technology stack identification**:
   ```
   "What frameworks and libraries does this project use?"
   ```

3. **Entry point discovery**:
   ```
   "Show me the main entry points and how the application starts"
   ```

4. **Configuration analysis**:
   ```
   "Explain the configuration files and their purposes"
   ```

5. **Dependency mapping**:
   ```
   "Trace the flow from the main controller to the service layer"
   ```

### Expected Outcomes

- Quickly understand unfamiliar codebases
- Identify key architectural patterns
- Learn to ask effective exploration questions

[← Back to Table of Contents](#table-of-contents)

## Lab 3: Test Generation

**Duration**: 15 minutes  
**Goal**: Generate comprehensive test suites with Claude Code

### Setup

Use the same project from Lab 2, focusing on service classes or core business logic.

### Exercises

1. **Unit test generation**:
   ```
   "Create unit tests for the [ServiceName] class with comprehensive coverage"
   ```

2. **Edge case identification**:
   ```
   "What edge cases should I test for the [methodName] method? Generate tests for them"
   ```

3. **Integration test creation**:
   ```
   "Create integration tests for the [ControllerName] that test the full request/response cycle"
   ```

4. **Mock setup**:
   ```
   "Generate tests with proper mocking for external dependencies"
   ```

5. **Test data generation**:
   ```
   "Create realistic test data and fixtures for these test cases"
   ```

### Expected Outcomes

- Understand automated test generation
- Learn about edge case identification
- Practice test-driven development with AI assistance

[← Back to Table of Contents](#table-of-contents)

## Lab 4: Documentation Creation

**Duration**: 15 minutes  
**Goal**: Generate professional documentation with Claude Code

### Setup

Continue with your chosen project, focusing on undocumented areas.

### Exercises

1. **README generation**:
   ```
   "Create a comprehensive README file for this project including setup, usage, and examples"
   ```

2. **API documentation**:
   ```
   "Generate API documentation for all the REST endpoints in this application"
   ```

3. **Code comments**:
   ```
   "Add meaningful JavaDoc/docstring comments to the main service classes"
   ```

4. **Architecture documentation**:
   ```
   "Create an architectural overview document explaining the system design"
   ```

5. **Troubleshooting guide**:
   ```
   "Generate a troubleshooting guide for common issues with this application"
   ```

### Expected Outcomes

- Create professional-quality documentation
- Learn different documentation formats
- Understand how to maintain documentation

[← Back to Table of Contents](#table-of-contents)

## Lab 5: Legacy Code Refactoring

**Duration**: 15 minutes  
**Goal**: Modernize legacy code using Claude Code assistance

### Setup

Use the `exercises/java/shopping-service` (Grails/Groovy) project or any legacy code you have available.

### Exercises

1. **Code modernization**:
   ```
   "Refactor this class to use modern Java features like records, switch expressions, and optional"
   ```

2. **Spring Boot updates**:
   ```
   "Update this Spring configuration to use modern Spring Boot patterns and annotations"
   ```

3. **Exception handling improvement**:
   ```
   "Improve the error handling in this service class with proper exception types and messages"
   ```

4. **Performance optimization**:
   ```
   "Review this code for performance issues and suggest optimizations"
   ```

5. **Security review**:
   ```
   "Review this controller for security vulnerabilities and suggest fixes"
   ```

### Expected Outcomes

- Learn systematic refactoring approaches
- Understand modern development patterns
- Practice security-focused code review

[← Back to Table of Contents](#table-of-contents)

## Lab 6: Advanced Workflows

**Duration**: 20 minutes  
**Goal**: Use advanced Claude Code features for complex tasks and real-world maintenance

### Setup

Navigate to the `exercises/python/weather-app` directory for this lab.

### Exercises

#### Part A: Advanced Claude Code Features (10 minutes)

1. **Plan Mode usage**:
   - Press `Shift+Tab+Tab` to activate Plan Mode
   ```
   "Plan a comprehensive improvement to add error handling and logging to this Flask application"
   ```
   - Review the plan before execution
   - Execute step by step

2. **CLAUDE.md creation**:
   ```
   "Create a CLAUDE.md file for this weather app with Python coding standards, dependencies, and project context"
   ```

   Note that the built-in slash command `/init` creates the `CLAUDE.md` file, but you can simply ask Claude to create it if you like.

3. **Custom slash command**:
   ```
   "Help me create a custom slash command for updating Python dependencies safely"
   ```

#### Part B: Feature Enhancement (10 minutes)

4. **Error handling enhancement**:
   ```
   "Add comprehensive error handling to this Flask application including proper status codes and user-friendly error pages"
   ```

5. **Logging integration**:
   ```
   "Implement structured logging throughout the application with appropriate log levels"
   ```

6. **Configuration management**:
   ```
   "Improve the configuration system to support environment-specific settings"
   ```

7. **Testing validation**:
   ```
   "Create tests to verify the new error handling and logging functionality works correctly"
   ```

### Expected Outcomes

- Master advanced Claude Code features
- Create reusable project configurations
- Learn systematic feature enhancement workflows
- Practice comprehensive application improvement with AI assistance
- Understand enterprise development practices

[← Back to Table of Contents](#table-of-contents)

## Tips for Success

### Effective Prompting
- Be specific about what you want to achieve
- Provide context about your goals and constraints
- Use iterative refinement for complex tasks
- Include examples when possible

### Best Practices
- Start with clean git state before major changes
- Commit checkpoints regularly during development
- Review all AI-generated code before accepting
- Test generated code thoroughly

### Common Issues and Solutions

**Issue**: Claude Code doesn't understand the project  
**Solution**: Ask it to explore the project first: "Analyze this project structure"

**Issue**: Generated code doesn't follow project conventions  
**Solution**: Create a CLAUDE.md file with your coding standards

**Issue**: Tests fail after code generation  
**Solution**: Ask Claude to fix: "These tests are failing, please analyze and fix them"

**Issue**: Code is too verbose or not optimized  
**Solution**: Request refinement: "Make this code more concise and efficient"

## Next Steps

After completing these labs:

1. **Practice regularly**: Use Claude Code for daily development tasks
2. **Share with team**: Introduce colleagues to effective workflows
3. **Customize**: Create project-specific CLAUDE.md files and slash commands
4. **Iterate**: Refine your prompting techniques based on results
5. **Stay updated**: Follow Claude Code updates and new features

## Additional Resources

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
- [Best Practices Guide](https://www.anthropic.com/engineering/claude-code-best-practices)
- [MCP Server Directory](https://github.com/modelcontextprotocol/servers)