---
permalink: index.html
---

# Custom Source Repository for the winget.exe

This repository contains an example of a custom source repository for the [Windows Package Manager Client](https://github.com/microsoft/winget-cli) (aka `winget.exe`). We demonstate how to install a dummy `fake-app` application using `winget` from a non-standard location.

## Prerequisites

* Windows 10 64-bit and later
* [Windows Package Manager Client](https://github.com/microsoft/winget-cli/releases)

## Usage

* Configure the Windows to accept third-party applications:

<img src="/img/win-settings.png" alt="Windows Settings" width="800" />

* Run in command line:

    ```
    winget source add fake-repo https://winget.shamil.ru
    winget install fake-app
    ```

## License

Source code is licensed under the [MIT license](LICENSE).
