# pandoc-markdown-template

## Introduction

This template allows you to write documents in markdown extended with LaTeX, and convert them to gorgeous PDFs using pandoc. It is based on the [Eisvogel template](https://github.com/Wandmalfarbe/pandoc-latex-template).

## Installation

To use this template, you need to have [pandoc](https://pandoc.org/), [LaTeX](https://www.latex-project.org/), and [Python](https://www.python.org/) installed on your system.

## Usage

1. Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r scripts/requirements.txt
```

2. Write your document in markdown and put them in the `src` directory.
3. Configure the `build-conf.toml` file to your liking.
4. Run the build script:

```bash
python3 scripts/build.py
```

5. Your PDF will be in the `out` directory.
