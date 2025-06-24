# Claude Code Training Presentation Development

## Project Guidelines

This is a comprehensive Slidev presentation for Claude Code training, targeting professional developers and enterprise teams.

## Build Commands
- `pnpm dev` - Start development server with hot reload
- `pnpm build` - Build for production
- `pnpm export` - Export to PDF

## Content Standards
- Focus on practical, enterprise-ready examples
- Use Java/Spring Boot as primary technology examples
- Include real-world use cases from Anthropic teams
- Maintain professional tone suitable for corporate training
- Keep slides concise and readable (avoid text overflow)
- **Developer-to-developer approach** - Course is by developers for developers, avoid marketing/sales content

## Slide Design Principles
- **Avoid "Bullet-riddled corpse" anti-pattern** - Never create slides dense with bullet points
- **Many slides with few lines** - Prefer multiple focused slides over cramped multi-column layouts
- **One concept per slide** - Each slide should cover a single, clear idea
- **Minimize cognitive load** - Audience should grasp content at a glance
- **Progressive disclosure** - Break complex topics into logical slide sequences
- **White space is valuable** - Don't feel compelled to fill every slide completely

## Current Architecture
- Built with Slidev framework using Seriph theme
- Main content in slides.md with 110+ slides
- Comprehensive coverage from basics to advanced features
- Integration of latest Claude Code features (Plan Mode, Remote MCP, SDKs)
- Refactored to eliminate "bullet-riddled corpse" anti-pattern

## Recent Updates
- **Major refactoring** - Split dense slides to follow "many slides with few lines" principle
- **Eliminated bullet-riddled corpse** - Converted 12+ problematic slides into focused, digestible content
- **Improved layouts** - Fixed column layouts and centering issues for better readability
- **Comprehensive layout fixes** - Fixed slide dividers, progressive reveals, content overflow, and alignment issues
- **Separated exercises from main presentation** - Created dedicated labs.md for hands-on practice
- **Added exercise projects** - Real-world codebases in exercises/ directory for practical training
- Added Plan Mode functionality (Shift+Tab+Tab activation)
- Enhanced MCP section with remote server capabilities and OAuth authentication
- Added Claude Code SDKs (TypeScript/Python) for programmatic integration
- Updated with latest Claude Code 1.0+ features including Sonnet 4 model
- Removed marketing-focused content in favor of developer-to-developer approach

## Refactoring Completed
- Course Overview → 2 focused slides (What You'll Learn, Course Structure)
- Understanding the Interface → 4 slides (Command Mode, Auto-Accept, Plan Mode, Key Features)
- Plan Mode → 2 slides (How to Activate, Perfect For)
- File Editing & Refactoring → 3 slides (Core Capabilities, Java Modernization, Spring Updates)
- Model Context Protocol → 3 slides (What is MCP, GitHub Server, Osquery Server)
- Claude Code SDKs → 2 slides (Available SDKs, Key Capabilities)
- Future Developments → 3 slides (Emerging Capabilities, Technical Evolution, Workflow Integration)
- Real-World Success Stories → 2 slides (Dev/Data Science, Security/Marketing)
- Good Practices → 2 slides (Development Best Practices, Session Management)
- Available MCP Servers → 2 slides (Development Tools, Enterprise Tools)
- Key Takeaways → 3 slides (Transform Process, Technical Excellence, Strategic Integration)

## Content Organization

### Main Presentation (slides.md)
1. Installation and setup fundamentals
2. Core Claude Code features and interfaces  
3. Advanced capabilities (Plan Mode, MCP, SDKs)
4. Best practices and enterprise workflows
5. Real-world success stories and case studies

### Hands-On Labs (labs.md)
1. Lab 1: First Steps (5 minutes)
2. Lab 2: Code Exploration (10 minutes)
3. Lab 3: Test Generation (15 minutes)
4. Lab 4: Documentation Creation (15 minutes)
5. Lab 5: Legacy Code Refactoring (15 minutes)
6. Lab 6: Documentation Generation (15 minutes)

### Exercise Projects (exercises/)
- **Python**: weather-app (Flask), flask-api (refactoring practice)
- **JavaScript**: lyrics-trainer (TypeScript web app)
- **Java**: certificate-service (Spring Boot PDF), shopping-service (REST API)

## Presentation Delivery Notes
- 5-hour course format with hands-on exercises
- July 2025 first delivery planned
- Target audience: Professional developers and enterprise teams
- Include latest features as "cutting-edge" content