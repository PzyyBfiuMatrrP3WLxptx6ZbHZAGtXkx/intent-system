# @j-tech-japan/intent-cli-linux-arm64

Self-contained `intent-cli` binary for Linux ARM64 (aarch64).

This package contains a pre-built binary that includes the .NET runtime.
No .NET SDK or runtime installation is required on the target machine.

## Installation

```bash
npm install @j-tech-japan/intent-cli-linux-arm64
```

## Usage

```bash
npx intent-cli --version
```

Or add to your PATH:

```bash
export PATH="$(npm bin):$PATH"
intent-cli --version
```
