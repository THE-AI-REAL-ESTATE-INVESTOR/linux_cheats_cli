# Linux Cheats CLI 🚀

## About
- **What it is:** A command-line tool with a web page that shows Linux command cheat sheets, built as a learning project.
- **Business:** learning
- **Status:** inactive since 2024-12
- **Source:** agent research 2026-11-04

A beautiful and interactive command-line tool for displaying Linux command cheat sheets with a modern web interface. Powered by The AI Real Estate Investor.

Brought to you by [The AI Real Estate Investor](https://www.theairealestateinvestor.com)

![Linux Cheats CLI Banner](assets/images/banner.png)

## Features ✨

- 📚 Comprehensive Linux command reference
- 🌐 Beautiful web-based interface
- 🎨 Modern, responsive design
- 🔍 Easy-to-read command tables
- 🚀 Quick local server setup
- 🎁 Hidden easter eggs
- 🔄 Automatic browser launch
- 💡 Helpful mnemonics for each command

## Installation 🛠️

### Prerequisites

- Python 3.7+
- pandoc
- pip

### Installing the Package

+ > 📝 **Note:** Package will be available on PyPI soon! Currently only installable from source.
+ 
1. Install system dependencies:

```bash
# Ubuntu/Debian
sudo apt-get install pandoc python3-pip

# macOS
brew install pandoc

# Windows
choco install pandoc
```

2. Install the package:

```bash
# Clone the repository
git clone https://github.com/theaireinvestor/linux-cheats-cli.git
cd linux-cheats-cli

# Install dependencies
pip install -r requirements.txt

# Install in development mode
pip install -e .
```

## Usage 💻

After installation, the tool will automatically:
1. Show the CLI version with colorful command tables
2. Start the web interface in your default browser

You can also run specific modes:

```bash
# Show both CLI and web interface (default)
linux-cheats

# Only show CLI version
linux-cheats --cli

# Only start web interface
linux-cheats --web

# Start web interface without opening browser
linux-cheats --web --no-browser
```

## Command Categories 📋

1. Basic Commands
2. File Management
3. User Management
4. Disk and System Info
5. Networking
6. Permissions and Ownership

Each command includes:
- Command syntax
- Purpose
- Helpful mnemonic
- Usage example

## Project Structure 🗂️

```
linux-cheats-cli/
├── src/
│   └── linux_cheats_cli/
│       ├── public/
│       │   ├── assets/
│       │   │   ├── css/
│       │   │   └── images/
│       │   ├── templates/
│       │   └── linux_cheats.txt
│       ├── utils/
│       │   ├── convert_to_md.py
│       │   └── template.py
│       ���── main.py
├── setup.py
└── README.md
```

## Development 🔧

### Setting Up Development Environment

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Install development dependencies
pip install -e ".[dev]"
```

### Running Tests

```bash
pytest
```

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Powered By 🌟

[The AI Real Estate Investor](https://www.theairealestateinvestor.com)
- Join our AI Community
- Follow us on [Facebook](https://www.facebook.com/aireinvestor)
- Get more AI tools and tips in our [AI Revolutionaries Club](https://www.theairealestateinvestor.com/club)

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Thanks to all contributors
- Special thanks to The AI Real Estate Investor community
- Inspired by the need for better Linux command reference tools

## Support 💪

If you find this tool helpful, please:
- ⭐ Star this repository
- 🐛 Report any issues
- 💡 Suggest new features
- 🤝 Consider contributing

---

Made with ❤️ by [The AI Real Estate Investor](https://www.theairealestateinvestor.com)