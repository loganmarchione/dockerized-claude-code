# claude-code-dockerized

## Usage

```
HOST_UID=$(id -u) \
HOST_GID=$(id -g) \
PROJECT_DIR="$HOME/path/to/your/files" \
docker compose run --build --rm claude
```