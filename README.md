# HTML Learning Sandbox

[![CI](https://github.com/shxamill/testing/actions/workflows/ci.yml/badge.svg)](https://github.com/shxamill/testing/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A small personal sandbox for learning HTML and GitHub workflows.

## Project contents

| Path | Purpose |
| --- | --- |
| `index.html` | Minimal HTML5 starter page for future HTML experiments. |

## Run locally

No build step or dependencies are required. Open `index.html` directly in a browser, or start a local server from the repository root:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Validate local assets

Run `python scripts/check_assets.py` to check that local HTML and CSS references point to files inside the repository. The same check runs in GitHub Actions on pushes and pull requests.

## Project status

This is a learning repository, not a production application. Examples may be incomplete while exercises are in progress.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Community and security

See [CONTRIBUTING.md](CONTRIBUTING.md), [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), [SECURITY.md](SECURITY.md), and [SUPPORT.md](SUPPORT.md).
