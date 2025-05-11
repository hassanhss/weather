# Weather Project

A Python application that provides weather information using the National Weather Service (NWS) API.

## Features

- Get weather alerts for a US state
- Get weather forecast for a location by latitude and longitude

## Requirements

- Python 3.11 or higher
- Dependencies:
  - httpx
  - mcp[cli]

## Installation

```bash
# Clone the repository
git clone https://github.com/hassanhss/weather.git
cd weather

# Install dependencies
pip install -e .
```

## Usage

Run the main application:

```bash
python main.py
```

Or use as an MCP server:

```bash
python weather.py
```

## License

MIT
