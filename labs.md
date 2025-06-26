# Claude Code Training Labs

This document contains hands-on exercises for learning to use Claude Code for professional development workflows.

## Table of Contents

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
- Java/Spring Boot development environment

## Lab 1: First Steps with Claude Code

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
- `exercises/java/shopping-service` (REST API)
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

Use the `exercises/java/shopping-service` project or any legacy code you have available.

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

**Duration**: 15 minutes  
**Goal**: Use advanced Claude Code features for complex tasks

### Setup

Create a new branch in your project: `git checkout -b claude-improvements`

### Exercises

1. **Plan Mode usage**:
   - Press `Shift+Tab+Tab` to activate Plan Mode
   ```
   "Plan a comprehensive improvement to add user authentication to this application"
   ```
   - Review the plan before execution
   - Execute step by step

2. **CLAUDE.md creation**:
   ```
   "Create a CLAUDE.md file for this project with coding standards, build commands, and project context"
   ```

3. **Custom slash command**:
   ```
   "Help me create a custom slash command for generating Spring Boot service classes"
   ```

4. **Git integration**:
   ```
   "Commit all our improvements with appropriate commit messages"
   ```

5. **Pull request creation**:
   ```
   "Create a pull request for our improvements with a detailed description"
   ```

### Expected Outcomes

- Master advanced Claude Code features
- Create reusable project configurations
- Integrate AI assistance into git workflows

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

**Issue**: Claude Code doesn't understand project structure  
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
- [Community Examples](https://github.com/anthropics/claude-code-examples)