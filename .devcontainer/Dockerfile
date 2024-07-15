# See images from: https://github.com/devcontainers/images
ARG VARIANT="ubuntu-24.04"
FROM mcr.microsoft.com/devcontainers/base:${VARIANT} AS final

# Setup extensions volume provisions
ARG USERNAME=vscode
RUN mkdir -p "/home/$USERNAME/.vscode-server/extensions" \
    && chown -R "$USERNAME" \
    "/home/$USERNAME/.vscode-server"
