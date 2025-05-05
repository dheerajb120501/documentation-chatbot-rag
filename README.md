# Documentation Chatbot RAG

A chatbot application for documentation using Retrieval-Augmented Generation (RAG).

## Project Overview

This project implements a documentation chatbot that uses RAG techniques to provide accurate and contextually relevant responses based on documentation content.

## Local Setup

### Prerequisites

- Git
- [uv](https://github.com/astral-sh/uv) - Modern Python package manager

### Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:dheerajb120501/documentation-chatbot-rag.git
   cd documentation-chatbot-rag
   ```

2. Set up a virtual environment with uv:
   ```bash
   # Create and activate a virtual environment
   uv venv
   
   # Activate the virtual environment
   # On macOS/Linux:
   source .venv/bin/activate
   # On Windows:
   # .venv\Scripts\activate
   ```

### Running the Application

To run the application:

```bash
uv run main.py
```

### Managing Dependencies

To add new dependencies to your project:

```bash
# Add a dependency to pyproject.toml and install it
uv add package-name

# To add a development dependency
uv add --dev package-name