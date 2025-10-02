# Contributing Guidelines

  ## Branch Strategy
  - `main` - production-ready code
  - `develop` - integration branch for features
  - `feature/*` - new features (e.g., `feature/test-builder`)
  - `bugfix/*` - bug fixes
  - `hotfix/*` - urgent production fixes

  ## Workflow
  1. Create a feature branch from `develop`
  2. Make your changes
  3. Write/update tests
  4. Ensure code passes linting
  5. Submit PR to `develop` branch
  6. Request review from at least one team member
  7. Address review feedback
  8. Merge after approval

  ## Code Standards
  - Use consistent formatting (configure Prettier/ESLint)
  - Write descriptive commit messages
  - Comment complex logic
  - Write tests for new features
  - Keep functions focused and small

  ## Commit Message Format
  type(scope): brief description

  - Detailed explanation if needed

  Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

  ## Pull Request Guidelines
  - Link related issues
  - Describe what changed and why
  - Include screenshots for UI changes
  - Ensure CI passes

