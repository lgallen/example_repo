# CLAUDE.md - AI Assistant Guidelines

## Repository Overview

**Project:** example_repo
**Type:** Springboard/starter template repository
**Status:** Minimal starter - ready for initialization with your chosen technology stack

This is a minimal example repository designed as a starting point for new projects. It currently contains only a README and git configuration.

## Current Structure

```
example_repo/
├── README.md          # Project description
├── CLAUDE.md          # This file - AI assistant guidelines
└── .git/              # Git version control
```

## Development Status

- **No application code** - Repository is intentionally minimal
- **No dependencies** - No package managers or dependency files configured
- **No build system** - No build tools or scripts set up
- **No CI/CD** - No automated workflows configured
- **No tests** - No testing framework established

## Getting Started

When initializing this repository for a specific project:

1. **Choose your technology stack** and add appropriate configuration files
2. **Set up project structure** with standard directories (src/, tests/, docs/, etc.)
3. **Add dependency management** (package.json, requirements.txt, go.mod, etc.)
4. **Configure development tools** (.gitignore, linting, formatting)
5. **Set up CI/CD** as needed
6. **Update this CLAUDE.md** with project-specific guidelines

## Git Workflow

### Branch Naming

- Feature branches: `claude/<feature-name>-<session-id>`
- Main development happens on feature branches
- Always push with `-u origin <branch-name>`

### Commit Conventions

- Use clear, descriptive commit messages
- Start with an imperative verb (Add, Fix, Update, Remove, etc.)
- Keep the subject line concise (50 chars or less preferred)

### Current Git Configuration

- Remote: GitHub (lgallen/example_repo)
- Default branch workflow: Feature branch → PR → Main

## Guidelines for AI Assistants

### Before Making Changes

1. **Read existing files** before modifying them
2. **Understand the current state** of the repository
3. **Check for existing patterns** and follow them consistently
4. **Verify file paths** before creating new files

### Code Quality

- Keep changes minimal and focused
- Avoid over-engineering - solve the immediate problem
- Don't add features beyond what's requested
- Follow existing code style when present

### File Operations

- Prefer editing existing files over creating new ones
- Don't create documentation files unless explicitly requested
- Keep directory structure flat until complexity warrants nesting

### Testing

- Add tests when implementing new features (once test framework is set up)
- Run existing tests before committing changes
- Don't commit code that breaks existing tests

## Updating This File

As this repository grows, update this CLAUDE.md to include:

- Technology stack details and versions
- Build and test commands
- Project architecture overview
- Key files and their purposes
- Development environment setup instructions
- Code style and conventions specific to the project
- Common tasks and how to accomplish them

---

*Last updated: 2026-01-25*
