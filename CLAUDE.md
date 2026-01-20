# CLAUDE.md - AI Assistant Guide for kats_experiments

This file provides guidance for AI assistants working on this repository.

## Repository Overview

**kats_experiments** is an experimental playground repository for prototyping, testing ideas, and exploring new concepts. It serves as a sandbox for quick experiments without the constraints of production code.

## Repository Structure

This is currently an empty repository ready for experiments. As the repository grows, organize code as follows:

```
kats_experiments/
├── CLAUDE.md           # AI assistant guidelines (this file)
├── README.md           # Project overview and documentation
├── experiments/        # Individual experiment directories
│   └── <experiment>/   # Each experiment in its own folder
├── scripts/            # Utility scripts and tools
├── docs/               # Additional documentation
└── shared/             # Reusable code across experiments
```

## Development Workflow

### Starting a New Experiment

1. Create a new directory under `experiments/` with a descriptive name
2. Include a README.md in each experiment folder explaining:
   - Purpose of the experiment
   - How to run it
   - Key findings or results
3. Keep experiments self-contained when possible

### Git Conventions

- **Branch naming**: Use descriptive branch names (e.g., `experiment/feature-name`)
- **Commit messages**: Write clear, descriptive commit messages
  - Use present tense ("Add feature" not "Added feature")
  - Include context for why changes were made
- **Keep commits atomic**: One logical change per commit

### Code Style

Since this is an experiments repo, flexibility is key, but maintain:

- **Readability**: Write code that's easy to understand
- **Documentation**: Add comments for non-obvious logic
- **Clean up**: Remove dead code and unused files when an experiment concludes

## Common Tasks

### Creating a New Experiment

```bash
mkdir -p experiments/<experiment-name>
cd experiments/<experiment-name>
# Create your experiment files
# Add a README.md describing the experiment
```

### Running Experiments

Each experiment should document its own run instructions in its README.md. Common patterns:

- **Python**: `python experiments/<name>/main.py`
- **Node.js**: `node experiments/<name>/index.js`
- **Shell scripts**: `./experiments/<name>/run.sh`

## AI Assistant Guidelines

### When Working on This Repository

1. **Ask clarifying questions** if the experiment purpose is unclear
2. **Keep experiments isolated** - don't modify other experiments unless requested
3. **Document as you go** - add README files and comments
4. **Prefer simple solutions** - this is an experiments repo, not production code
5. **Clean up** - remove temporary files and debugging code before committing

### What to Avoid

- Over-engineering solutions for simple experiments
- Breaking existing experiments when adding new ones
- Committing sensitive data (API keys, passwords, etc.)
- Creating deeply nested directory structures

### Helpful Patterns

- Use environment variables for configuration
- Include sample data or mock data when needed
- Add `.gitignore` entries for generated files and dependencies

## Environment Setup

No specific environment setup is required yet. Individual experiments may have their own requirements documented in their respective README files.

## Contact & Ownership

Repository: `ninjaboy/kats_experiments`

---

*Last updated: 2026-01-20*
