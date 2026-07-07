# Common Vale alerts

## Overview

Vale reports alerts based on the configured writing standards. Understanding these alerts helps you improve the clarity, consistency, and readability of your documentation.

This page describes some of the most common alerts reported by the Google Developer Documentation Style Guide.

## Google.Passive

### Description

Identifies sentences written in the passive voice.

### Example

**Instead of**

> Customer records are managed by the application.

**Write**

> The application manages customer records.

### Best practice

Prefer active voice when it improves clarity.

---

## Google.Headings

### Description

Checks whether headings follow sentence case.

### Example

**Instead of**

```text
Configure Billing Rules
```

**Write**

```text
Configure billing rules
```

### Best practice

Use sentence case for all headings.

---

## Google.Acronyms

### Description

Identifies acronyms that may be unfamiliar to readers.

### Example

**Instead of**

> Configure the LDC.

**Write**

> Configure the Local Distribution Company (LDC).

### Best practice

Define unfamiliar acronyms on first use.

---

## Google.Parens

### Description

Identifies unnecessary use of parentheses.

### Example

**Instead of**

> Configure billing rules (if applicable).

**Write**

> If applicable, configure billing rules.

### Best practice

Use parentheses only when they improve clarity.

---

## Google.OxfordComma

### Description

Checks for the use of the Oxford comma in lists.

### Example

**Instead of**

> Billing, reporting and analytics

**Write**

> Billing, reporting, and analytics

### Best practice

Use the Oxford comma in lists.

---

## Google.EmDash

### Description

Checks for spaces before and after an em dash.

### Example

**Instead of**

```text
Billing — Reporting
```

**Write**

```text
Billing—Reporting
```

### Best practice

Use em dashes consistently.

---

## Best practices

When reviewing Vale alerts:

- Read the alert message carefully.
- Review the surrounding context.
- Apply the recommendation only if it improves the writing.
- Do not accept suggestions automatically.

## Checklist

Before publishing documentation, verify that:

- Common Vale alerts have been reviewed.
- Changes improve readability.
- Documentation follows the approved writing standard.

## References

- Vale Documentation
- Google Developer Documentation Style Guide
