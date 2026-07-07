# Installing Vale

## Overview

Vale is available for Windows, macOS, and Linux. Install Vale on your development machine before using it to review documentation.

## Install Vale

=== "macOS"

    Install Vale using Homebrew.

    ```bash
    brew install vale
    ```

=== "Windows"

    Install Vale using WinGet.

    ```powershell
    winget install errata-ai.Vale
    ```

=== "Linux"

    Follow the installation instructions for your Linux distribution in the Vale documentation.

## Verify the installation

Run the following command to verify that Vale is installed.

```bash
vale --version
```

Example output:

```text
vale version 3.15.1
```

## Update Vale

Keep Vale up to date to receive the latest features, bug fixes, and writing rules.

=== "macOS"

    ```bash
    brew upgrade vale
    ```

=== "Windows"

    ```powershell
    winget upgrade errata-ai.Vale
    ```

## Uninstall Vale

=== "macOS"

    ```bash
    brew uninstall vale
    ```

=== "Windows"

    ```powershell
    winget uninstall errata-ai.Vale
    ```

## Checklist

Before continuing, verify that:

- Vale is installed.
- The `vale --version` command runs successfully.
- Vale is available from the terminal.

## Next steps

Continue to **Configuring Vale** to configure Vale for your documentation project.

## References

- Vale Documentation
