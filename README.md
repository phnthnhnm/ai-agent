# AI Agent

AI Agent is a toy project written in Python that demonstrates a very simple AI agent using the Google GenAI package. The agent can perform basic tasks and interact with the file system within the working directory.

## Features
- Simple AI agent logic
- Uses Google GenAI for language processing
- File system access (restricted to the working directory)

## Disclaimer
> [!CAUTION]
> This project allows the AI agent to access and modify files in the working directory. Use with caution. Do not run this project in directories containing sensitive or important files. The author is not responsible for any data loss or unintended consequences.

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd ai-agent
   ```

2. **Create your environment variables:**
   - Copy the provided `env.example` file to `.env`:
     ```sh
     cp env.example .env
     ```
   - Edit `.env` and fill in the required values (see below).


3. **Install dependencies:**
   
   This project uses [uv](https://github.com/astral-sh/uv) for fast Python dependency management.
   ```sh
   uv pip install -r pyproject.toml
   ```

4. **Run the project:**
   ```sh
   uv run main.py "your prompt here" [--verbose]
   ```

## Environment Variables
See `env.example` for the required variables. You must provide your own Google GenAI API key.
