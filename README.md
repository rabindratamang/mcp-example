# MCP Example Service

This is an example service built using the MCP (Model Control Protocol) framework. The service demonstrates how to create a simple weather service with tools, resources, and prompts.

## Features

- Weather information retrieval through tools
- Weather data as resources
- Weather report prompt generation
- FastAPI-based server implementation

## Prerequisites

- Python 3.12 or higher
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd mcp-example
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Linux/Mac
# or
.venv\Scripts\activate  # On Windows
```

3. Install dependencies:
```bash
pip install -e .
```

## Usage

Run the server:
```bash
python server.py
```

The server provides the following functionality:

### Tools
- `get_weather(location)`: Returns current weather information for a specified location

### Resources
- `weather://{location}`: Provides weather data as a resource

### Prompts
- `weather_report(location)`: Generates a weather report prompt for a specified location

## Project Structure

- `server.py`: Main server implementation with MCP tools, resources, and prompts
- `pyproject.toml`: Project configuration and dependencies
- `main.py`: Entry point for the application

## Development

This project uses Python 3.12+ and follows modern Python packaging standards with `pyproject.toml`.
