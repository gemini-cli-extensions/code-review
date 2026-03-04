# Gemini CLI Code Review Extension

The Code Review extension is an open-source Gemini CLI extension, built to enhance your repository's code quality.  The extension adds a new command to Gemini CLI that analyzes code changes to identify a variety of code quality issues.

This extension is brought to you by the authors of the [Gemini Code Assist GitHub App](https://github.com/apps/gemini-code-assist), which provides code reviews directly in your GitHub pull requests.

## Installation

Install the Code Review extension by running the following command from your terminal *(requires Gemini CLI v0.4.0 or newer)*:

```bash
gemini extensions install https://github.com/gemini-cli-extensions/code-review
```

If you do not yet have Gemini CLI installed, or if the installed version is older than 0.4.0, see
[Gemini CLI installation instructions](https://github.com/google-gemini/gemini-cli?tab=readme-ov-file#-installation).

## Use the extension

### Reviewing code changes

The Code Review extension adds the `/code-review` command to Gemini CLI which analyzes code changes on your current branch for quality issues.

### Reviewing a pull request

The Code Review extension adds the `/pr-code-review` command to Gemini CLI which analyzes code changes on your pull request for quality issues.

To use this extension for a pull request, you need to [enable](https://github.com/google-gemini/gemini-cli/blob/main/docs/tools/mcp-server.md) the [github mcp server](https://github.com/github/github-mcp-server), and provide pull request information. You can either provide through `/pr-code-review link/to/pull/request` or by [configuring](https://github.com/google-gemini/gemini-cli/blob/main/docs/reference/configuration.md#environment-variables-and-env-files) the following environment variables:
- `REPOSITORY`: The github repository which contains the pull request.
- `PULL_REQUEST_NUMBER`: The pull request number that need the code review.
- `ADDITIONAL_CONTEXT`: Additional context or specific area that should focus on.

## Resources

- [Gemini CLI extensions](https://github.com/google-gemini/gemini-cli/blob/main/docs/extensions/index.md): Documentation about using extensions in Gemini CLI
- [Blog post](https://blog.google/technology/developers/gemini-cli-extensions/): Announcement of Gemini CLI Extensions
- [GitHub issues](https://github.com/gemini-cli-extensions/code-review/issues): Report bugs or request features

## Legal

- License: [Apache License 2.0](https://github.com/gemini-cli-extensions/code-review/blob/main/LICENSE)
