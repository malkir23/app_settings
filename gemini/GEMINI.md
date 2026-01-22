### Important Notes
- The codebase uses Ukrainian comments in `ruff.toml` configuration
- Uses `uv` as the Python package manager instead of pip
- All async operations use modern Python async/await patterns
-
## Gemini Added Memories
- Always use UUIDv7 when generating UUIDs.
- The user wants me to use `datetime.now(timezone.utc)` for getting the current time.
- Format all string outputs using single quotes for the outer string. If a nested string or quote is needed inside, wrap it with double double quotes: ""like this"". Do not use double quotes for outer strings.
