# Claude Code Training Course Development

This project contains the materials for a comprehensive training course on Claude Code, aimed at professional software developers.

## Core Materials

- **`slides.md`**: The main Slidev presentation. It is structured to provide a logical learning path, from basic setup to advanced features and best practices.
- **`exercises.md`**: The primary document for in-class, hands-on work. It contains specific, project-based exercises that students will perform on the provided codebases.
- **`lab_handout.md`**: A supplementary reference guide for students. It contains generic prompts, tips, and troubleshooting advice that they can use during the class and apply to their own projects afterward.
- **`exercises/`**: A directory of diverse sample projects used for all demos and exercises. It includes:
    - **Python**: A simple `weather-app` and a poorly-written `flask-api` for refactoring practice.
    - **JavaScript/TypeScript**: A `lyrics-trainer` web application.
    - **Java**: A modern `certificate-service` (Spring Boot) and a legacy `shopping-service` (Grails).

## Development Workflow

1.  **Run the presentation:** `pnpm dev`
2.  **Build for production:** `pnpm build`
3.  **Export to PDF/PPTX:** `pnpm export` (see `package.json` for options)

## Guiding Principles

- **Practical First:** The course is designed to get students productive with the tool as quickly as possible.
- **Real-World Scenarios:** Exercises use a variety of realistic codebases, from modern to legacy, showcasing the tool's versatility.
- **Best Practices:** The course emphasizes professional workflows, such as the "branch-first" approach to experimentation and safety.
