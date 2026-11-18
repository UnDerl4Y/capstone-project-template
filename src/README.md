# Source Code

This directory contains the source code and implementation files for the project.

## Organization

Organize the source code according to your project's architecture, components, and implementation requirements. You are free to choose your own directory structure, programming languages, and frameworks.

## Environment Configuration

- Use a `.env` file locally to configure environment variables required by the application.
- Create a `.env.example` file containing the required environment variable names and safe example or empty values.
- Never commit or upload actual API keys, access tokens, passwords, connection strings, or other sensitive credentials.
- If you already have a `.env` file, create a sanitized `.env.example` from it. Retain the variable names but replace all actual secrets with empty or example values. Do not simply rename a file containing real credentials.
- Ensure the actual `.env` file is not included in your submission.

## Dependencies and Generated Files

- Include the necessary dependency and configuration files, such as `requirements.txt`, `package.json`, or equivalent files used by your project.
- Do not upload virtual environments such as `venv/` or `.venv/`.
- Remove any existing virtual environment folder from the repository before uploading your project.
- Do not include unnecessary cache files, temporary files, or generated dependencies.

## Implementation

Add your source code, configuration files, and other implementation-related resources here. Include additional folders or files whenever required.