
name: Golden Snake Engine

on:
  schedule:
    - cron: "17 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

concurrency:
  group: golden-snake
  cancel-in-progress: true

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: UmerSk-dev
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=%23FFD76A&color_dots=%230D0B07,%233C3015,%237C6126,%23C49B37,%23F5D76E

      - name: Publish SVGs to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
