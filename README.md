# MIH
name: Publish to registries

on:
  workflow_call:

jobs:
  crates_io:
    name: Publish to Crates.io
    runs-on: ubuntu-latest
    steps:
      - name: Publish packages
        run: |
          echo "::warning::TODO: add a Crates.io publish logic"

  npm:
    name: Publish to npmjs.com
    runs-on: ubuntu-latest
    steps:
      - name: Publish packages
        run: |
          echo "::warning::TODO: add a npmjs.com publish logic"
