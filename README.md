# Claude Code Training Course

A comprehensive training presentation and hands-on lab exercises for using Claude Code in professional software development.

## 🚀 Course Materials

This repository contains all the materials for the Claude Code Training course:

- **`slides.md`**: The main Slidev presentation.
- **`exercises.md`**: Concrete, project-based exercises for students to complete during the course.
- **`lab_handout.md`**: A supplementary "cheat sheet" with generic prompts and best practices that students can take with them.
- **`exercises/`**: A directory containing diverse projects in Python, JavaScript/TypeScript, and Java, which serve as the basis for all demos and exercises.

## 🏃‍♀️ Running the Presentation

1.  **Install dependencies:**
    ```bash
    pnpm install
    ```

2.  **Start the development server:**
    ```bash
    pnpm dev
    ```

3.  Open your browser at <http://localhost:3030>

## 🛠️ Available Scripts

- `pnpm dev` - Start development server with hot reload.
- `pnpm build` - Build for production.
- `pnpm export` - Export to PDF.
- `pnpm export --format pptx --output claude-code-training.pptx` - Export to PowerPoint.

For exporting presentations, you may need to install Playwright first:
```bash
pnpm install -D playwright-chromium
pnpm exec playwright install
```

## 👤 Author

**Ken Kousen**
- Email: ken.kousen@kousenit.com
- Website: kousenit.com
