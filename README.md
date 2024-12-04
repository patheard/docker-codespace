# Docker Codespaces
An example of how to setup [Codespaces](https://code.visualstudio.com/docs/remote/codespaces) and run Docker.  This repo defines a simple devcontainer that includes:

- Docker
- Python 3.13
- [VS Code GitHub Copilot extension](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

Once the Codespace starts, you will be able to run Docker commands like so:

```sh
docker run -it alpine:latest sh
```

If you want to attach to a running Codespace from VS Code, install the [Codespaces extension](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces).

## Local development
The devcontainer can also be used for localhost development if you have Docker and the [VS Code Devcontainers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed.