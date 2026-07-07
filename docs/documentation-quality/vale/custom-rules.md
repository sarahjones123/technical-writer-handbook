# Custom rules

## Overview

Vale includes built-in style packages, such as the Google Developer Documentation Style Guide. However, every documentation team has its own terminology, writing conventions, and documentation standards.

Custom rules allow you to extend existing style guides and enforce organization-specific writing standards.

## When to create custom rules

Consider creating custom rules when:

- Your organization uses product-specific terminology.
- You want to enforce internal writing standards.
- Existing Vale rules do not cover your requirements.
- Writers frequently make the same writing mistakes.
- You want to improve consistency across the documentation.

## Common use cases

Custom rules can help enforce:

- Product terminology
- Approved acronyms
- UI writing conventions
- Preferred word choices
- Prohibited words or phrases
- Company-specific writing standards

## Example

A documentation team decides to always use **End user** instead of **End User**.

A custom Vale rule can identify incorrect usage and recommend the approved term.

## Best practices

When creating custom rules:

- Start with an existing style guide before creating custom rules.
- Create custom rules only when there is a clear business need.
- Keep rules simple and easy to understand.
- Document the purpose of every custom rule.
- Review custom rules regularly as writing standards evolve.

## Rule organization

Store custom rules in a dedicated style package.

```text
styles/
├── Google/
└── TW/
    ├── Terminology.yml
    ├── UIWriting.yml
    ├── ProductNames.yml
    └── Vocabulary/
```

## Checklist

Before creating a custom rule, verify that:

- The rule is not already covered by the existing style guide.
- The writing standard has been documented.
- The rule improves documentation consistency.
- The rule benefits all contributors.

## References

- Vale Documentation
- Google Developer Documentation Style Guide
