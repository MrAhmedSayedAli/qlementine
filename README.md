<div align="center">
	<img height="50" src="branding/logo.svg">
</div>

# Qlementine

[![License: MIT](https://img.shields.io/badge/license-MIT-green)](https://mit-license.org/)
[![CMake version](https://img.shields.io/badge/CMake-3.17.5+-064F8C?logo=cmake)](https://www.qt.io)
[![C++ version](https://img.shields.io/badge/C++-17-00599C?logo=++)](https://www.qt.io)
[![Qt version](https://img.shields.io/badge/Qt-5.15.3+-41CD52?logo=qt)](https://www.qt.io)
[![Qt version](https://img.shields.io/badge/Qt-6.0.0+-41CD52?logo=qt)](https://www.qt.io)

Modern QStyle for desktop Qt5/Qt6 applications.

---

### Table of Contents

- [Requirements](#requirements)
- [Features](#features)
- [Usage](#usage)
- [Creator](#creator)
- [License](#license)

---

## Requirements

- Windows, MacOS or Linux.
- [CMake 3.17.5+](https://cmake.org/download)
- [Qt 5.15.3+ or Qt 6.0.0+](https://www.qt.io/download-qt-installer)

## Features

This library contains:

- A custom `QStyle` named `QlementineStyle`, that implements all the necessary API to give a modern look and feel to your Qt application. It's a drop-in replacement for the default `QStyle`.
- Lots of utilities to help you write beautiful `QWidgets`.
- A collection of new `QWidgets` that are missing in Qt's standard collection, such as `Switch`.

## Usage

See [documentation](dcos/usage.md). Basically, you just need to add Qlementine as a Git submodule and link with it with CMake.

## Creator

**Olivier Cléro** | [email](mailto:oclero@pm.me) | [website](https://www.olivierclero.com) | [github](https://www.github.com/oclero) | [gitlab](https://www.gitlab.com/oclero)

## License

**Qlementine** is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
