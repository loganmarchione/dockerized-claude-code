# claude-code-dockerized

[![Lint](https://github.com/loganmarchione/dockerized-claude-code/actions/workflows/lint.yml/badge.svg)](https://github.com/loganmarchione/dockerized-claude-code/actions/workflows/lint.yml)

## Usage

```
HOST_UID=$(id -u) \
HOST_GID=$(id -g) \
PROJECT_DIR="$HOME/path/to/your/files" \
docker compose run --build --rm claude
```
