# mdfolio

My tiny static site generator, ~100 lines of Python

Built for my own use; public in case it helps someone.

## Getting started

```bash
pip install -r requirements.txt
```

## Highlights

- Index page with post list by date
- Markdown posts with fenced code and tables
- RSS feed generation
- Single template, plain str.format, no Jinja

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
