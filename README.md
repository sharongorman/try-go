# Adventures in Go

Using a dev container to keep my local environment clean.
A simple repo with a helloworld.go.

## Instructions:
1. Clone this repo.
2. Open vsCode --> Run Command "Dev Containers: Open Folder in Container..."
3. Open a terminal in your dev container

```bash
go run ./cmd/cli
```

## Decisions
1. Keep vscode setting in workplace settings.  This enables them to apply if the code is edited locally rather than in a dev container.
2. Use a Dockerfile to define my docker image.  Again, this enables the dev container to be used as a standalone docker and limits dependency on devcontainer spec.

## References:
1. Understanding dev containers: (VSCode - Developing inside a Container)[https://code.visualstudio.com/docs/devcontainers/containers]
2. Configuring my vs code to support go : https://blog.boot.dev/golang/format-on-save-vs-code-golang/
3. Understanding packages and modules : [An Introduction to Packages, Imports and Modules by Alex Edwards](https://www.alexedwards.net/blog/an-introduction-to-packages-imports-and-modules)
