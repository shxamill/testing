# HTML Learning Sandbox

A small personal sandbox for learning HTML and GitHub workflows.

## Project contents

| Path | Purpose |
| --- | --- |
| `index.html` | Entry point for HTML experiments. It is currently an empty starter file. |

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

No repository-level open-source license is currently provided. Do not assume that public availability grants permission to reuse or redistribute the code.
