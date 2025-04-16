# Base image with .NET Core 3.1 SDK
FROM mcr.microsoft.com/dotnet/core/sdk:3.1

# Install useful CLI tools
RUN apt-get update && apt-get install -y \
    git \
    curl \
    vim \
    && rm -rf /var/lib/apt/lists/*

