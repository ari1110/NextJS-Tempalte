FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

# Install only the necessary libraries
RUN apt-get update && apt-get install -y \
    sudo \
    libnss3 \
    libnspr4 \
    libatk1.0-0 \
    libatk-bridge2.0-0 \
    libcups2 \
    libdrm2 \
    libxkbcommon0 \
    libxcomposite1 \
    libxdamage1 \
    libxfixes3 \
    libxrandr2 \
    libgbm1 \
    libasound2 \
    python3 \
    python3-pip \
    python3-venv \
    pipx \
    jq \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*