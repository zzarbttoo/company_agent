# Company Agent Service

This is a FastAPI-based service for company agent management.

## Project Structure
```
company_agent/
├── src/                  # Source code
│   ├── api/             # API routes
│   ├── core/            # Core business logic
│   ├── models/          # Data models
│   ├── services/        # Service layer
│   ├── repositories/    # Data access layer
│   └── utils/           # Utility functions
├── tests/               # Test files
├── config/             # Configuration files
└── main.py             # Application entry point
```

## Setup
1. Install Poetry (if not already installed):
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

2. Install dependencies:
```bash
poetry install
```

3. Run the application:
```bash
poetry run start
# Or alternatively:
poetry run uvicorn main:app --reload
```

## Testing
Run tests using pytest:
```bash
poetry run pytest
```

## Managing Dependencies
- Add a new dependency:
```bash
poetry add package-name
```

- Add a development dependency:
```bash
poetry add --group dev package-name
```

- Update dependencies:
```bash
poetry update
```