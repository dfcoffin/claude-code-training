# Weather App Exercise

## Overview
This is a simple Python weather application that fetches weather data from an API. The code works but has several areas for improvement using Claude Code.

## Learning Objectives
- Use Claude Code to explore and understand an unfamiliar codebase
- Generate comprehensive tests for API interactions
- Improve error handling and edge cases
- Create professional documentation

## Exercise Tasks

### Task 1: Code Exploration (10 minutes)
1. Start Claude Code in this directory
2. Ask Claude to analyze the project structure
3. Have Claude explain the main components and data flow
4. Identify potential issues or improvements

**Example prompts:**
```
"Give me an overview of this weather app"
"Explain how the API integration works"
"What design patterns are used here?"
"Identify any potential bugs or issues"
```

### Task 2: Test Generation (15 minutes)
1. Ask Claude to generate unit tests for the main functions
2. Request tests for edge cases (invalid input, API failures)
3. Add integration tests for the API calls
4. Implement mock objects for external dependencies

**Example prompts:**
```
"Create comprehensive unit tests for the weather service"
"Add tests for error scenarios like network failures"
"Generate tests for invalid city names and API responses"
"Set up proper mocking for the external API calls"
```

### Task 3: Error Handling (10 minutes)
1. Improve error handling throughout the application
2. Add proper exception types
3. Implement user-friendly error messages
4. Add logging for debugging

**Example prompts:**
```
"Improve error handling in the API client"
"Add custom exceptions for different error scenarios"
"Implement proper logging throughout the application"
```

### Task 4: Documentation (10 minutes)
1. Generate a comprehensive README
2. Add docstrings to all functions
3. Create usage examples
4. Document the API requirements

**Example prompts:**
```
"Create a professional README for this project"
"Add detailed docstrings following Python conventions"
"Generate usage examples for the documentation"
```

## Setup Instructions

1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your API key (if required):
   ```bash
   export WEATHER_API_KEY="your-api-key-here"
   ```

## Success Criteria
- [ ] All main functions have comprehensive test coverage
- [ ] Error handling covers all external API interactions
- [ ] Documentation clearly explains setup and usage
- [ ] Code follows Python best practices
- [ ] All tests pass successfully

## Tips
- Use Claude's ability to understand the codebase quickly
- Let Claude suggest improvements you might not have considered
- Try different Claude Code modes for different tasks
- Don't forget to commit your changes as you go

## Bonus Challenges
- Add weather forecast functionality
- Implement caching to reduce API calls
- Create a simple CLI interface
- Add support for multiple weather services