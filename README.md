# OSC-EM Documentation

This repository contains the source for the OSC-EM documentation website, built with MkDocs and deployed to https://osc-em.github.io.

## Local Development

### Prerequisites

- Python 3.x
- pip3

### Installation

```bash
pip3 install -r requirements.txt
```

### Running Locally

```bash
mkdocs serve
```
or, if installed the requirements in a venv:
```bash
source venv/bin/activate && mkdocs serve
```

Then visit http://127.0.0.1:8000 in your browser.

### Building the Site

```bash
mkdocs build
```

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch via GitHub Actions.
