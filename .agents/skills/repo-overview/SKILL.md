# Admin-Panel — Repo Overview

## Repository Structure

This is a newly initialized repository that is in its early scaffolding phase. Below is a detailed breakdown of the current contents:

```
.
├── .git/              # Git version control directory
│   ├── HEAD           # Points to refs/heads/main
│   ├── config         # Repo-level git configuration
│   ├── hooks/         # Default Git hook samples (no custom hooks configured)
│   ├── objects/       # Git object store
│   └── refs/          # Branch and tag references
├── README.md          # Project README (contains only the heading "# Admin-Panel")
```

### Key Observations

- **No application source code** has been added yet — no `src/`, `app/`, `lib/`, or similar directories exist.
- **No dependency/build configuration files** are present (e.g., no `package.json`, `pyproject.toml`, `Cargo.toml`, `Makefile`, `Dockerfile`, `docker-compose.yml`, or similar).
- **No framework or language** has been chosen for the project yet.
- **No static assets, configs, or environment files** (e.g., `.env`, `.eslintrc`, `tsconfig.json`) exist.
- **No CI/CD configuration** (e.g., `.github/workflows/`, `.gitlab-ci.yml`, `Jenkinsfile`) is present.
- **No pre-commit hooks** (e.g., `.pre-commit-config.yaml`, `.husky/`) are configured.

### Branches

| Branch | Description |
|--------|-------------|
| `main` | Default branch. Contains only the initial commit with `README.md`. |
| `devin/1767730526-dummy-test-change` | Test branch with minor README edits (used to verify Devin access). |

## Git Workflow

- **Default branch:** `main`
- **Branch naming convention:** `devin/<unix-timestamp>-<descriptive-slug>`
  - Example: `devin/1767730526-dummy-test-change`
  - Generate timestamp with: `date +%s`
  - Use lowercase and hyphens only for the slug
- **Merge strategy:** Merge commits (no rebase/force-push)
- **No branch protection rules** are currently configured.

## Build / Dev Server

- No build system or dev server is configured yet.
- Once the project is scaffolded, update this section with:
  - Install command (e.g., `npm install`, `pip install -r requirements.txt`)
  - Dev server command (e.g., `npm run dev`, `python manage.py runserver`)
  - Build command (e.g., `npm run build`)
  - Any required environment variables or `.env` setup

## Linting & Formatting

- No linter or formatter is configured.
- Once added, update this section with:
  - Lint command (e.g., `npm run lint`, `ruff check .`)
  - Format command (e.g., `npm run format`, `ruff format .`)
  - Type-check command (e.g., `npm run typecheck`, `mypy .`)

## Testing Conventions

### Current State

- **No test framework** is set up (no `jest.config.*`, `pytest.ini`, `vitest.config.*`, or similar).
- **No test directories** exist (e.g., no `tests/`, `__tests__/`, `spec/`).
- **No test scripts** are defined in any configuration file.

### Guidelines for Future Setup

When tests are added to this project, follow these conventions:

1. **Test location:** Place tests in a dedicated directory (e.g., `tests/` or `__tests__/`) mirroring the source structure.
2. **Test naming:** Use descriptive names that reflect what is being tested (e.g., `test_user_creation.py`, `UserCard.test.tsx`).
3. **Test command:** Document the test runner command here once chosen (e.g., `npm test`, `pytest`, `cargo test`).
4. **Coverage:** If a coverage tool is configured, document how to run it and any minimum thresholds.
5. **CI integration:** When CI is set up, ensure tests run automatically on PRs and document the expected workflow.
6. **Manual testing:** For UI components, note any local URLs or steps needed to visually verify changes.

### Running Tests

- No tests can be run at this time. Update this section once a test framework is in place with:
  - `<test-command>` — Run all tests
  - `<test-command> <path>` — Run a specific test file
  - `<test-command> --coverage` — Run tests with coverage report

## Secrets & Environment Variables

- No secrets or environment variables are required at this time.
- No `.env.example` or `.env.template` file exists.

## Notes

- This is a greenfield project. All sections above should be updated as the project evolves.
- No documentation beyond the basic README exists yet.
- When scaffolding is added, re-evaluate and update this SKILL.md with concrete commands and conventions.
