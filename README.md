<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<div align="center">
  <h1>Dlang GUI Samples</h1>
  <p>GUI toolkit samples for multiple GUI libraries in D.</p>
  <p>
    <a href="https://github.com/dlang-supplemental/dlang-gui-samples/issues">Report Bug</a>
    ·
    <a href="https://github.com/dlang-supplemental/dlang-gui-samples/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

A collection of sample "Hello World" projects for various D language GUI toolkits, organized into Wrappers and Native libraries. List taken from [GUI Libraries on the D Wiki](https://wiki.dlang.org/GUI_Libraries).

### Repository Structure

#### Wrappers
These are D bindings or wrappers around existing C/C++ GUI libraries.

- **[GtkD](Wrappers/gtkd)**: D bindings for GTK+.
- **[DWT](Wrappers/dwt)**: A port of the Eclipse SWT library to D.
- **[dqt (w0rp)](Wrappers/dqt-w0rp)**: D bindings for Qt.
- **[DQt (tim)](Wrappers/dqt-tim)**: Another set of D bindings for Qt.
- **[dqml](Wrappers/dqml)**: QML bindings for D.
- **[QtE5](Wrappers/qte5)**: Qt5 bindings for D.
- **[wxD](Wrappers/wxd)**: D bindings for wxWidgets.
- **[FltkD](Wrappers/fltkd)**: D bindings for FLTK.
- **[tkd](Wrappers/tkd)**: D bindings for Tcl/Tk.
- **[dtk](Wrappers/dtk)**: A toolset-independent GUI library.
- **[sciter-dport](Wrappers/sciter-dport)**: D bindings for Sciter.
- **[awebview](Wrappers/awebview)**: A WebView wrapper for D.
- **[DerelictLibui](Wrappers/derelict-libui)**: Derelict bindings for libui.
- **[libuid](Wrappers/libuid)**: D bindings for libui.
- **[Delta](Wrappers/delta)**: A lightweight GUI library.

#### Native
These are GUI libraries written specifically for D or with heavy D-specific design.

- **[DFL](Native/dfl)**: D Forms Library (Win32).
- **[DFL Rayerd fork](Native/dfl-rayerd)**: A fork of DFL.
- **[DFL2](Native/dfl2)**: An updated version of DFL.
- **[dformlib](Native/dformlib)**: Another DFL fork.
- **[DGui](Native/dgui)**: A graphic library for Windows.
- **[fxLib](Native/fxlib)**: A native D GUI library.
- **[DlangUI](Native/dlangui)**: Cross-platform GUI for D.
- **[DQuick](Native/dquick)**: A native D GUI library.

### VS Code

- Open the **repository root** for catalog-wide defaults (`.vscode/settings.json` recommends Code-D and enables Dub auto-fetch).
- **File → Open Folder** on a specific sample (e.g. `Wrappers/gtkd`) when you want that project's Dub root and its own `.vscode/settings.json` (add per-sample formatters, `dubPath`, or debug configs there).

## Usage

Each sample is a standalone DUB project. Navigate to the project directory and run:

```bash
dub run
```

*Note: Some libraries may require external dependencies (e.g., GTK, Qt, Tcl/Tk) to be installed on your system.*

## Contact

DLang Supplemental — dlang@devcentr.org

Project Link: https://github.com/dlang-supplemental/dlang-gui-samples

Site: https://dlang-supplemental.github.io

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/dlang-supplemental/dlang-gui-samples.svg?style=for-the-badge
[contributors-url]: https://github.com/dlang-supplemental/dlang-gui-samples/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dlang-supplemental/dlang-gui-samples.svg?style=for-the-badge
[forks-url]: https://github.com/dlang-supplemental/dlang-gui-samples/network/members
[stars-shield]: https://img.shields.io/github/stars/dlang-supplemental/dlang-gui-samples.svg?style=for-the-badge
[stars-url]: https://github.com/dlang-supplemental/dlang-gui-samples/stargazers
[issues-shield]: https://img.shields.io/github/issues/dlang-supplemental/dlang-gui-samples.svg?style=for-the-badge
[issues-url]: https://github.com/dlang-supplemental/dlang-gui-samples/issues
