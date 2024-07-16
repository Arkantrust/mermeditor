# mermeditor

A real-time web editor for creating and editing Mermaid diagrams, with GitHub integration for saving and committing diagrams.

## Features

- Real-time Mermaid diagram rendering
- GitHub OAuth authentication
- Save and commit diagrams to GitHub repositories

## Setup

### Backend

1. Deploy the Go OAuth backend to Google Cloud Functions.
2. Set the environment variables `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET`.

### Frontend

1. Host the static files (index.html, styles.css, script.js) on GitHub Pages.

## Usage

1. Open the editor at [https://yourusername.github.io/mermaid-editor](https://yourusername.github.io/mermaid-editor).
2. Log in with GitHub and start editing your diagrams.
3. Save and commit diagrams to your GitHub repository.

## Coming soon

GitLab and Gitea integrations. https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
