# Codex .NET Environment Bootstrap

This script installs the .NET SDK (version 9.0) into a Codex-compatible environment, enabling C# development in ChatGPT Codex before official support is available.

## What It Does

- Installs the .NET SDK 9.0 into `/root/.dotnet`
- Configures environment variables (`DOTNET_ROOT`, `PATH`)
- Persists configuration to `.bashrc` for future sessions
- Verifies installation with `dotnet --version`

## Usage

Copy and paste `setup-dotnet.sh` into your Codex project environment.

![image](https://github.com/user-attachments/assets/b72560c6-81ef-4bc5-b374-31bd1b6b382b)

> ⚠️ **MIT License – Not Official**  
> This project is **not affiliated with or officially supported**. Use at your own risk under the terms of the MIT License.

