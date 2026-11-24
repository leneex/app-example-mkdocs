# MkDocs

Example [MkDocs](https://www.mkdocs.org/) static site. MkDocs is a static site generator for project documentation written in Markdown.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/site` |
| Install command | leave empty |
| Build command | `mkdocs build` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# virtual environment and dependencies
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt

# run in development mode
mkdocs serve

# build for production
mkdocs build
```

Requires Python 3.9 or later.
