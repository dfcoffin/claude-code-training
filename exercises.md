# Claude Code Training: Demos and Exercises

This document outlines suggested demos and exercises for the projects in the `exercises` directory. The projects offer a diverse mix of languages, frameworks, and code quality, perfect for showcasing the capabilities of an AI coding assistant.

---

### Core Best Practice: The "Branch-First" Workflow

Before starting any exercise that involves significant code changes, get into the habit of creating a new Git branch. This is the most important safety measure you can take. It isolates your work, allows for fearless experimentation, and makes it easy to discard changes if they don't work out, all without affecting the `main` branch.

**Recommended Branching Strategy for Exercises:**

Since this is a training course with multiple projects in one repository, use a simple local branching approach:

1. **Create a branch for each exercise:** Use descriptive names based on the exercise
   - Examples: `flask-api-refactor`, `weather-app-forecast`, `lyrics-trainer-debug`
   
2. **Work locally:** No need to push branches - this is just for practice and experimentation

3. **Easy reset:** If you want to start over, simply:
   ```bash
   git checkout main
   git checkout -b new-attempt
   ```

4. **Commit as you go:** Create checkpoints for your progress
   ```bash
   git commit -m "test: add pytest suite"
   git commit -m "refactor: extract database logic"
   ```

**Example Prompt:** `Using git, create a new feature branch called 'flask-api-refactor' and switch to it.`

---

### 1. Python: `flask-api` (The "Awful" Project)

**Primary Demo Vehicle.** This project is a prime candidate for demonstrating large-scale refactoring, code cleanup, and adding foundational best practices. Use this project to tell a continuous story of improvement.

**Suggested Demos & Exercises:**

*   **Demo: Initial Triage & Understanding**
    *   **Prompt:** `Analyze this project and identify the top 3-5 areas for improvement in terms of code quality, security, and maintainability.`

*   **Demo: Branching for Safety**
    *   Demonstrate the "branch-first" workflow before making any changes.
    *   **Prompt:** `Using git, create a new feature branch called 'flask-api-refactor' and switch to it.`

*   **Exercise: Add a Safety Net (Testing)**
    *   **Prompt:** `Write unit tests for the main endpoints in app.py. Use the pytest framework and mock any database interactions.`

*   **Demo: Major Refactoring**
    *   **Prompt:** `Now that we have tests, let's refactor app.py. Separate the database logic, models, and API routes into their own modules within a new application structure.`

*   **Exercise: Git Integration - Committing Changes**
    *   After refactoring, have students use the assistant to commit their work.
    *   **Prompt:** `Commit the changes on this branch with a Conventional Commit message that describes the refactoring.`

*   **Exercise: Documentation**
    *   **Prompt:** `Create a complete README.md for this project, including setup instructions and API endpoint documentation.`

*   **Exercise: Vulnerability Remediation**
    *   This exercise demonstrates a real-world security workflow.
    *   **Step 1: Identify Vulnerabilities.** Have students ask the assistant to check for outdated packages.
    *   **Prompt:** `Analyze the requirements.txt file. Are these packages up-to-date? Are there any known security vulnerabilities in these specific versions?`
    *   **Step 2: Plan the Upgrade.** Ask the assistant to create a plan to upgrade the packages to secure versions.
    *   **Prompt:** `Create a plan to upgrade the packages in requirements.txt to the latest secure versions. What are the potential breaking changes I should be aware of?`
    *   **Step 3: Execute the Upgrade.** Have the students instruct the assistant to perform the upgrade.
    *   **Prompt:** `Now, please update the requirements.txt file to the latest stable and secure versions of Flask, Werkzeug, and MarkupSafe.`
    *   **Step 4: Verify the Fix.** After updating, students should run the tests to ensure the application still works.
    *   **Prompt:** `Run the tests to ensure the application is still functional after the upgrade.`

---

### 2. Python: `weather-app` (The "Beginner" Project)

This project is perfect for showing how to iteratively add features and work with different types of files.

**Suggested Demos & Exercises:**

*   **Exercise: Image Analysis - From Wireframe to Code**
    *   Use the provided wireframe to generate the initial UI.
    *   **Prompt:** `Analyze the weather-app-wireframes.jpg and generate the HTML and CSS for the main home page.`

*   **Exercise: Add a New Feature**
    *   **Prompt:** `Modify the application to add a 5-day forecast page that is linked from the main city weather view.`

*   **Demo: Error Handling & Robustness**
    *   **Prompt:** `Add error handling to the weather data fetching logic. If the external API fails or returns an error, display a user-friendly error page.`

---

### 3. JavaScript/TypeScript: `lyrics-trainer`

A modern web project with an existing test suite, ideal for demonstrating workflows on a realistic, contemporary stack.

**Suggested Demos & Exercises:**

*   **Demo: Working with an Existing Test Suite**
    *   **Prompt:** `Review the existing tests in the tests/ directory. Now, write a new test file for src/script.ts that verifies the main application logic.`

*   **Exercise: Bug Fixing**
    *   Introduce a bug and have students use the assistant and the test suite to find and fix it.
    *   **Prompt:** `The lyrics are not advancing correctly when the user types. Run the tests to confirm the failure, then analyze src/script.ts to find and fix the bug.`

---

### 4. Java: `shopping-service` (Old Grails Project)

This project is a classic "legacy modernization" scenario, perfect for showing how an AI assistant can act as a subject matter expert for older or unfamiliar technologies.

**Suggested Demos & Exercises:**

*   **Demo: "Teach Me This Framework"**
    *   **Prompt:** `This is a Grails project. Explain the purpose of the key directories like 'grails-app/controllers', 'grails-app/domain', and 'grails-app/views'.`

*   **Exercise: Understand and Translate Code**
    *   **Prompt:** `Explain the ProductController.groovy file. What are its main actions? Translate the 'list' action to an equivalent in Java with Spring Boot.`

*   **Demo: Modernization Plan**
    *   **Prompt:** `Think step-by-step and create a detailed plan to migrate this Grails project to a modern Spring Boot application. The new application should provide a JSON REST API instead of server-side views.`

---

### 5. Java: `certificate-service` (Modern Spring Boot Project)

This project represents a current, common stack, ideal for demonstrating advanced, best-practice development workflows.

**Suggested Demos & Exercises:**

*   **Demo: Advanced Test Generation**
    *   **Prompt:** `Write a test for the CertificateService class. Use Mockito to mock the repository dependency and verify that the service's methods are called correctly.`

*   **Exercise: Working with Build Files**
    *   **Prompt:** `Add the Spring Boot Actuator dependency to this project. Modify the build.gradle.kts file correctly to include it.`

*   **Exercise: Custom Commands for Workflow Automation**
    *   Showcase how to create a custom, project-specific command.
    *   **Prompt:** `Create a project-level custom command named /newcert. When I run '/newcert PDF', it should scaffold a new PdfCertificateController.java and a PdfCertificateService.java in the appropriate directories.`

*   **Demo: Deployment & DevOps Tasks**
    *   **Prompt:** `First, explain the heroku-deploy.sh script. Then, create a multi-stage Dockerfile to build and run this Spring Boot application efficiently.`