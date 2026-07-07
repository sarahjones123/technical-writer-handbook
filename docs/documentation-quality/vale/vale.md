# Vale

## Overview

Vale is a prose linter that helps technical writers improve the quality, consistency, and readability of documentation.

Unlike Markdownlint, which checks Markdown formatting, Vale analyzes the writing itself. It identifies issues related to grammar, style, capitalization, terminology, readability, and other writing conventions.

## Why use Vale?

Vale helps technical writers:

- Improve writing quality.
- Maintain a consistent writing style.
- Detect common writing issues early.
- Reduce review comments.
- Focus code reviews on content instead of writing style.

## What does Vale check?

Depending on the configured style guide, Vale can identify issues such as:

- Passive voice
- Inconsistent capitalization
- Incorrect heading style
- Unnecessary parentheses
- Acronyms
- Repeated words
- Word choice
- Punctuation
- Terminology

## Writing standard

This handbook uses the **Google Developer Documentation Style Guide** as the primary writing standard.

Vale validates documentation against the configured writing standards and reports suggestions, warnings, and errors.

## Best practices

When using Vale:

- Run Vale before submitting a pull request.
- Review every suggestion before making changes.
- Do not accept every suggestion automatically.
- Use judgment when applying writing recommendations.
- Follow the approved writing standard consistently.

## Checklist

Before submitting documentation, verify that:

- Vale completes without errors.
- Suggestions have been reviewed.
- Warnings have been addressed where appropriate.
- The documentation follows the approved writing standard.

## References

- Vale Documentation
- Google Developer Documentation Style Guide
