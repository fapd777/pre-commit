# Pre-commit
GitHub actions IaC pre-commit workflow.

## Usage

Add this file in your .github/workflows folder

```yml
name: Pre-Commit

on:
  pull_request:

jobs:
  build:
    uses: fapd777/pre-commit/.github/workflows/pre-commit.yml@main
```