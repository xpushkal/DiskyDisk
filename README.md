# DiskyDisk

DiskyDisk is a disk management and storage utility project focused on making storage inspection and operations simple, reliable, and developer-friendly.

This repository currently contains project docs and the initial scaffold. As implementation grows, this README can act as the single source of truth for setup, usage, and architecture.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Configuration](#configuration)
- [Development](#development)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

## Overview

DiskyDisk aims to provide a streamlined way to:

- Inspect storage devices and disk usage
- Run common disk-related operations safely
- Offer clear output for both CLI and future UI workflows

For detailed functional requirements and design notes, see `docs/DiskyDisk.pdf`.

## Features

Planned and in-progress capabilities:

- Device and partition discovery
- Disk usage summary and breakdown
- Health/status checks
- Safe operation mode with confirmation steps
- Extensible architecture for adding new disk tools

## Project Structure

```
DiskyDisk/
├── README.md
└── docs/
	└── DiskyDisk.pdf
```

## Getting Started

### Prerequisites

Add these based on your implementation stack:

- Runtime: Node.js / Python / Go (choose one)
- OS support: macOS (current), Linux/Windows (optional)

### Clone the Repository

```bash
git clone git@github.com:xpushkal/DiskyDisk.git
cd DiskyDisk
```

### Install Dependencies

Populate this once your stack is finalized.

Examples:

```bash
# Node.js
npm install

# Python
pip install -r requirements.txt
```

## Usage

Update this section when your entry point is ready.

Examples:

```bash
# Node.js example
npm run start

# Python example
python main.py
```

If your project is CLI-first, document commands like:

```bash
diskydisk scan
diskydisk usage --path /Volumes
diskydisk health --device disk0
```

## Configuration

Document environment variables and config files here.

Example format:

```env
DISKYDISK_ENV=development
DISKYDISK_LOG_LEVEL=info
DISKYDISK_SAFE_MODE=true
```

## Development

Recommended workflow:

1. Create a feature branch.
2. Implement changes with tests.
3. Run lint and test commands.
4. Open a pull request.

Example local quality checks:

```bash
# Node.js
npm run lint && npm test

# Python
ruff check . && pytest
```

## Roadmap

- [ ] Initial CLI scaffold
- [ ] Core disk inspection commands
- [ ] Rich output formatting (table/json)
- [ ] Automated tests
- [ ] Release v0.1.0

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b feat/your-feature`
3. Commit your changes
4. Push and open a pull request

## License

Add your preferred license (for example: MIT) in a `LICENSE` file.
