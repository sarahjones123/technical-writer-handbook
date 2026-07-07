# Markdownlint

## Overview

Markdownlint is a tool that checks Markdown files for formatting issues and helps maintain a consistent documentation style.

It identifies common formatting problems and encourages writers to follow established Markdown best practices.

## Why use Markdownlint?

Markdownlint helps:

- Improve documentation consistency.
- Reduce formatting errors.
- Improve readability.
- Simplify document reviews.
- Maintain a consistent writing style across the documentation.

## Current configuration

This handbook uses **markdownlint-cli2** to validate Markdown files.

Markdownlint is configured using the `.markdownlint.json` file located in the project root.

## Common rules

The following Markdownlint rules are commonly encountered during documentation development.

| Rule  | Description                               |
| ----- | ----------------------------------------- |
| MD009 | Trailing spaces                           |
| MD010 | Hard tabs                                 |
| MD013 | Line length                               |
| MD022 | Blank lines around headings               |
| MD029 | Ordered list numbering                    |
| MD032 | Blank lines around lists                  |
| MD040 | Language specified for fenced code blocks |
| MD047 | File ends with a single newline           |

## Running Markdownlint

Run Markdownlint for the entire project.

```bash
npx markdownlint-cli2 "docs/**/*.md"
```

## Best practices

Follow these practices when writing Markdown:

- Format documents consistently.
- Fix linting issues before creating a pull request.
- Use automatic formatting where possible.
- Review lint warnings instead of ignoring them.
- Keep Markdown simple and readable.

## Checklist

Before submitting documentation, verify that:

- Markdownlint completes without errors.
- Markdown formatting is consistent.
- Code blocks specify a language.
- Documents end with a single newline.
- Trailing spaces are removed.

## Scenario

Imagine a documentation team with five technical writers working on the same documentation repository.

Each writer has a different writing and formatting style:

- One writer uses tabs for indentation.
- Another uses spaces.
- One writer leaves trailing spaces.
- Another skips blank lines between headings and content.
- Some writers specify the language for code blocks, while others do not.

Although the documentation builds successfully, the Markdown files become inconsistent and difficult to maintain. Code reviews begin to focus on formatting issues instead of the quality of the content.

Markdownlint automatically identifies formatting issues and encourages every writer to follow the same Markdown conventions. As a result, documentation remains consistent, reviews become more efficient, and writers can focus on creating high-quality content instead of debating formatting preferences.

## References

- Markdownlint Documentation
