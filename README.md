## Collection of useful actions

Example:

````yaml
name: Workflow
on:
  push:
jobs:
  install-dependencies:
    runs-on: ubuntu-latest
    steps:
      - uses: airfocusio/github-actions/git-checkout@v1.0.0
      - uses: airfocusio/github-actions/setup-node@v1.0.0
      - uses: airfocusio/github-actions/cache-node@v1.0.0
````