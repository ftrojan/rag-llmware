# rag-llmware
Follow the https://www.youtube.com/watch?v=JjgqOZ2v5oU

# setup

```shell
brew install podman
podman machine init --now
podman run -d -p 27017:27017  -v mongodb-volume:/data/db --name=mongodb mongo:latest
pip install llmware
```

# tear down

```shell
podman machine stop
```