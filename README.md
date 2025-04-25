# a11y-cli-test

This repository is a simple setup to test and validate the `a11y-cli` accessibilty scanner inside a CI/CD environment.

It contains:

- A basic HTML page (`index.html`) with common accessibility issues
- A GitHub Actions workflow that automatically runs `a11y-cli` against the page on every push
- Uploaded accessbility audit report (`a11y-report.html`) as artifacts
