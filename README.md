# Countdown Timer

A countdown timer built with Python.

@dakota

## Features

- Simple and lightweight
- Multiple output formats (text, JSON, CSV)
- Config file support
- Input validation and error handling
- Extensible architecture

## Installation

```bash
git clone <repo-url>
cd countdown-timer
pip install -r requirements.txt
```

## Usage

```bash
# Basic usage
python main.py item1 item2 item3

# Output to file
python main.py item1 item2 -o output.txt

# JSON format
python main.py item1 item2 -f json

# Show version
python main.py -v
```

## Configuration

Edit `config.json`:

```json
{
  "output_format": "text",
  "verbose": false
}
```

## Testing

```bash
python -m pytest test_app.py -v
```

## License

MIT
