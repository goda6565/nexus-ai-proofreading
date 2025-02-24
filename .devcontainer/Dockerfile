FROM ghcr.io/astral-sh/uv:latest AS uv

FROM mcr.microsoft.com/vscode/devcontainers/base:bullseye
COPY --from=uv --chown=vscode: /uv /uvx /bin/