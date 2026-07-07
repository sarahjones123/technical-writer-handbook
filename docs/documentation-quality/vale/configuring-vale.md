# Configuring Vale

## Overview

After installing Vale, configure it to use the writing standards for your documentation project.

Vale reads its configuration from a `.vale.ini` file located in the project root.

## Create the configuration file

Create a file named `.vale.ini` in the root directory of your project.

Example:

```text
project/
├── docs/
├── styles/
├── .vale.ini
└── mkdocs.yml
```

## Basic configuration

The following configuration uses the Google Developer Documentation Style Guide.

```ini
StylesPath = styles

MinAlertLevel = suggestion

Packages = Google

[*.md]
BasedOnStyles = Google
```

## Configuration options

| Option          | Description                                |
| --------------- | ------------------------------------------ |
| `StylesPath`    | Directory that contains Vale styles.       |
| `MinAlertLevel` | Minimum alert level to report.             |
| `Packages`      | Style packages to install.                 |
| `BasedOnStyles` | Writing styles to apply to Markdown files. |

## Synchronize style packages

After saving the configuration file, download the configured style packages.

```bash
vale sync
```

## Verify the configuration

Run the following command to verify that Vale can locate the configuration file.

```bash
vale ls-config
```

The command displays the active configuration used by Vale.

## Validate documentation

Run Vale against a Markdown file.

```bash
vale docs/index.md
```

Run Vale against all Markdown files.

```bash
vale docs
```

## Best practices

- Store `.vale.ini` in the project root.
- Commit `.vale.ini` to source control.
- Keep the configuration consistent across the team.
- Review changes to the configuration during code reviews.

## Checklist

Before continuing, verify that:

- `.vale.ini` exists in the project root.
- The Google style package is installed.
- `vale sync` completes successfully.
- `vale ls-config` displays the active configuration.
- Vale analyzes your Markdown files successfully.

## Next steps

Continue to **Understanding Vale alerts** to learn how to interpret and resolve Vale suggestions, warnings, and errors.

## References

- Vale Documentation
- Google Developer Documentation Style Guide
