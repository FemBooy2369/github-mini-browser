# GitHub Mini-Browser & AI-GitHubSearcher

A terminal-based GitHub browser written in Rust with AI-powered repository search using Google Gemini.

## Features

- **GitHub Search** — Search repositories on GitHub.
- **AI Search** — Use natural language to find repositories with Gemini AI.
- **File Browser** — Browse and download repository files.
- **Terminal UI** — Interactive terminal interface built with Ratatui.

## Technologies

- Rust (Edition 2021)
- Ratatui
- Crossterm
- Tokio
- Reqwest
- Serde
- Google Gemini API
- GitHub REST API

## Requirements

- Rust and Cargo
- GitHub Personal Access Token
- Google Gemini API key

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Create a `.env` file in the project root:

```env
GITHUB_TOKEN=your_github_token
GEMINI_API_KEY=your_gemini_api_key
```

Build and run:

```bash
cargo run
```

## Usage

1. Launch the application.
2. Navigate through the terminal interface.
3. Search for GitHub repositories.
4. Try AI-powered search using natural language.
5. Browse repository files.

## Project Status

This project is currently under development. Some features, including AI search, may not work correctly yet.

## Security

**Never commit your `.env` file or API keys to GitHub.**

Make sure `.env` is listed in `.gitignore`.

## License

No license has been specified yet.
