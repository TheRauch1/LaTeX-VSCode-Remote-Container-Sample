
# LaTeX VS Code Remote - Containers Sample

## Steps
1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop)
1. Install [VS Code Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
1. Open this directory.
1. Execute `Remote-Containers: Reopen in Container` in the VS Code Command Palette.

## Explanation to the .devcontainer folder
- `Dockerfile`: Dockerfile for the container. It installs the dependencies for the project inside the container. A container is a virtual environment that is isolated from the host machine.
- `devcontainer.json`: Configuration file for the container. It specifies the Dockerfile to use, the extensions to install, and the settings to apply to VS Code inside the container.

Both files are required for VS Code Remote - Containers to work and highly customizable. You can find more information about them in the [official documentation](https://code.visualstudio.com/docs/remote/containers).

## Credits
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) - James-Yu
- [LaTeX Workshop - Sample](https://github.com/James-Yu/LaTeX-Workshop/tree/master/samples/docker) - James-Yu