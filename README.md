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

The Code Review extension adds the `/code-review` command to Gemini CLI which analyzes code changes on your current branch for quality issues.

## Resources

- [Gemini CLI extensions](https://github.com/google-gemini/gemini-cli/blob/main/docs/extensions/index.md): Documentation about using extensions in Gemini CLI
- [Blog post](https://blog.google/technology/developers/gemini-cli-extensions/): Announcement of Gemini CLI Extensions
- [GitHub issues](https://github.com/gemini-cli-extensions/code-review/issues): Report bugs or request features

## Legal

- License: [Apache License 2.0](https://github.com/gemini-cli-extensions/code-review/blob/main/LICENSE)
