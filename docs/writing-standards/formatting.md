# Document formatting

## Overview

Consistent formatting improves readability and makes documentation easier to scan, review, and maintain.

This section provides general formatting guidelines for creating clear and consistent technical documentation.

## Guidelines

Follow these formatting guidelines:

- Use sentence case for headings.
- Use numbered lists for procedures.
- Use bullet lists for unordered information.
- Format UI elements using backticks.
- Format file names and commands using backticks.
- Use fenced code blocks for code samples.
- Keep paragraphs short and focused.
- Use tables only when they improve readability.

## Best practices

### Headings

Use sentence case for all headings.

**Instead of**

```text
Configure Billing Rules
```

**Write**

```text
Configure billing rules
```

### Lists

Use numbered lists for sequential tasks.

```text
1. Create an LDC.
2. Configure the billing rules.
3. Save the configuration.
```

Use bullet lists for related information.

```text
- Customer details
- Billing information
- Contact information
```

### UI elements

Format UI elements using backticks.

**Instead of**

> Click Save.

**Write**

> Click `Save`.

### File names

Format file names using backticks.

Examples:

- `mkdocs.yml`
- `README.md`
- `package.json`

### Commands

Use fenced code blocks for commands.

```bash
mkdocs serve
```

### Code

Use fenced code blocks with the appropriate language.

```yaml
site_name: Technical Writer Handbook
theme:
  name: material
```

## Checklist

Before publishing documentation, verify that:

Headings use sentence case.
Lists are formatted consistently.
UI elements use backticks.
File names use backticks.
Commands use fenced code blocks.
Paragraphs are concise.
Tables improve readability.

## References

Google Developer Documentation Style Guide
