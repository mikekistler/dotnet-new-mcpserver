# Start with the latest tools
#FROM mcr.microsoft.com/dotnet/nightly/sdk:10.0.100-preview.7
FROM mcr.microsoft.com/devcontainers/dotnet:dev-10.0-preview

# Install the runtime from the most recent .NET LTS on top of that
COPY --from=mcr.microsoft.com/dotnet/sdk:8.0 /usr/share/dotnet /usr/share/dotnet

# Install the runtime from the current .NET STS release on top of that
COPY --from=mcr.microsoft.com/dotnet/sdk:9.0 /usr/share/dotnet /usr/share/dotnet
