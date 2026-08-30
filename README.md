# CAS CS 630 - Graduate Algorithms (Fall 2026)

This repository contains the source code and Markdown files used to build the official course website for **CAS CS 630: Graduate Algorithms** at Boston University (Fall 2026).

## Website Development & Deployment

This course website is built with **[MkDocs](https://www.mkdocs.org/)** using the **mkdocs-material** theme. It is automatically deployed to GitHub Pages via GitHub Actions.

### Local Development Setup

To make edits and preview changes locally before pushing:

1. **Clone the repository:**

    ```bash
    git clone [https://github.com/srtjanuario/2026.fall.cs630.git](https://github.com/srtjanuario/2026.fall.cs630.git)
    cd 2026.fall.cs630
    ```

2. **Install dependencies:**

    ```bash
    pip install mkdocs-material
    ```

3. **Serve the site locally:**

    ```bash
    mkdocs serve
    ```
    
    Open your browser and navigate to `http://127.0.0.1:8000/`.

### Deployment

Deployments are fully automated. Any push to the `main` branch triggers the GitHub Actions workflow (`.github/workflows/ci.yml`) that builds and publishes the updated site to the `gh-pages` branch.
