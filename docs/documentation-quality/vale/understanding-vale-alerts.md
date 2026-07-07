# Understanding Vale alerts

## Overview

Vale analyzes your documentation and reports issues based on the configured writing standards.

Each alert includes information that helps you identify the issue, locate it in the document, and determine whether it should be addressed.

## Alert format

A typical Vale alert looks like this:

```text
docs/getting-started/index.md
7:167 suggestion Use active voice instead of passive voice.
Google.Passive
```

## Understanding the alert

| Component                                    | Description                            |
| -------------------------------------------- | -------------------------------------- |
| `docs/getting-started/index.md`              | File containing the issue.             |
| `7:167`                                      | Line number and column number.         |
| `suggestion`                                 | Alert severity.                        |
| `Use active voice instead of passive voice.` | Description of the issue.              |
| `Google.Passive`                             | Writing rule that triggered the alert. |

## Alert severity

Vale reports the following alert levels:

| Severity   | Description                                |
| ---------- | ------------------------------------------ |
| Suggestion | A recommendation to improve the writing.   |
| Warning    | A potential issue that should be reviewed. |
| Error      | A rule violation that should be corrected. |

## Should every alert be fixed?

No.

Vale provides recommendations based on the configured writing standards. Review each alert before making changes.

Consider the following questions:

- Does the suggestion improve clarity?
- Does the suggestion preserve the intended meaning?
- Is the alert applicable to the current context?
- Does the documentation follow the team's writing standard?

## Best practices

When reviewing Vale alerts:

- Read the complete alert message.
- Understand why the rule was triggered.
- Review the surrounding content before making changes.
- Use judgment instead of accepting every suggestion automatically.
- Keep the reader's experience as the highest priority.

## Checklist

Before submitting documentation, verify that:

- All Vale errors have been resolved.
- Warnings have been reviewed.
- Suggestions have been evaluated.
- Changes improve the readability of the documentation.

## Next steps

Continue to **Common Google style rules** to learn about frequently reported Vale alerts and how to address them.

## References

- Vale Documentation
- Google Developer Documentation Style Guide
