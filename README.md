# PyxisIDE

### A Modern, All-in-One Multi-Language Development Environment

<p align="center">
  <img src="assets/pyxiside-banner.png" alt="PyxisIDE Banner" width="100%">
</p>

<p align="center">
  <strong>Write. Run. Inspect. Create.</strong>
  <br>
  A desktop IDE designed to bring Python, Java, and C# development together in one customizable workspace.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/Languages-Python%20%7C%20Java%20%7C%20C%23-6C63FF?style=for-the-badge" alt="Supported Languages">
  <img src="https://img.shields.io/badge/Interface-Customizable-8A2BE2?style=for-the-badge" alt="Customizable Interface">
  <img src="https://img.shields.io/badge/Distribution-Standalone%20EXE-2EA44F?style=for-the-badge" alt="Standalone Executable">
</p>

<p align="center">
  <a href="#-download">Download</a> •
  <a href="#-features">Features</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-keyboard-shortcuts">Shortcuts</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-about-the-project">About</a>
</p>

---

## Overview

**PyxisIDE** is a desktop integrated development environment built to make coding across multiple programming languages accessible from a single application.

Instead of switching between separate editors and terminal windows, PyxisIDE brings code editing, project navigation, program execution, terminal access, output inspection, and workspace customization into one unified environment.

Built with a focus on flexibility and practical usability, PyxisIDE offers a customizable interface, multi-file editing, automatic language recognition, integrated execution controls, and support for interactive console programs.

The goal is simple: **provide a development environment that feels powerful without making everyday coding unnecessarily complicated.**

### What makes PyxisIDE different?

- **One workspace, multiple languages:** Work with Python, Java, and C# in the same IDE.
- **Standalone distribution:** A large, packaged Windows executable designed to simplify installation and setup.
- **A customizable workspace:** Arrange development panels to suit your workflow.
- **Integrated execution:** Write and run code without leaving the application.
- **A personalized environment:** Explore 16 custom themes, including the signature Pyxis Midnight theme.
- **Built around usability:** Keyboard shortcuts, automatic indentation, code folding, and file management are integrated into the workflow.

---

## ✨ Features

### 1. Multi-Language Development

PyxisIDE supports three programming languages within the same development environment.

| Language | File Extension | Execution Support |
|---|---|---|
| Python | `.py` | Run Python scripts |
| Java | `.java` | Compile and run Java programs |
| C# | `.cs` | Compile and run C# programs |

The IDE identifies the language from the file extension, allowing you to work with different source files without manually switching the entire environment.

Interactive console input is supported, including common approaches such as Python's `input()`, Java's `Scanner`, and C#'s `Console.ReadLine()`.

### 2. Multi-Tab Code Editor

Work across multiple files without losing your place.

- Open multiple files in separate tabs.
- Switch between files quickly.
- Create new files and save existing ones.
- Use **Save As** to save files under a different name or location.
- Open individual files or entire project directories.
- Work with different supported programming languages in the same session.
- Use automatic indentation for cleaner code formatting.
- Navigate source code using line numbers and line highlighting.
- Collapse and expand code sections using code folding.
- Find and replace text within your code.

Whether you're editing a single script or navigating a multi-file project, PyxisIDE keeps your source files accessible in one workspace.

### 3. Project Explorer and File Management

Keep your projects organized through the integrated project explorer.

- Browse project directories.
- Open individual source files.
- Load entire folders as projects.
- Create and manage files from within the IDE.
- Work with connected and imported project files.
- Use drag-and-drop interactions where supported.
- Open the native Windows file explorer when needed.

The project explorer is designed to reduce unnecessary context switching and keep related source files within easy reach.

### 4. Integrated Execution Engine

PyxisIDE includes a custom execution engine that connects the editor with the program-running workflow.

Available execution controls include:

- **Run:** Execute the current program.
- **Stop:** Terminate a running program.
- **Output panel:** View program output and execution messages.
- **Interactive input:** Enter data into programs that request console input.
- **Native terminal access:** Work with a Windows command shell from within the IDE.
- **Error reporting:** View execution and compilation errors in the output area.

The IDE is designed to run one program at a time, keeping execution focused and avoiding multiple competing output sessions.

Each new run automatically clears the previous output, helping you distinguish the results of one execution from another.

### 5. Interactive Console Programs

Console applications often require more than printing text. They may ask questions, accept user input, and continue running based on the supplied values.

PyxisIDE supports interactive workflows for programs using standard input mechanisms, including:

```python
name = input("Enter your name: ")
print(f"Hello, {name}!")
```

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = scanner.nextLine();

        System.out.println("Hello, " + name + "!");
        scanner.close();
    }
}
```

```csharp
using System;

class Program {
    static void Main() {
        Console.Write("Enter your name: ");
        string name = Console.ReadLine() ?? "";

        Console.WriteLine($"Hello, {name}!");
    }
}
```

These examples illustrate the kinds of interactive console programs PyxisIDE is designed to support.

### 6. Customizable Workspace

Your development environment should adapt to you—not the other way around.

PyxisIDE features a customizable panel-based workspace. Arrange the coding editor, project explorer, output area, and terminal according to your preferences.

Workspace capabilities include:

- Repositioning supported interface panels.
- Organizing the editor and output areas around your workflow.
- Accessing terminal and project-navigation tools in the same environment.
- Saving workspace layout preferences across application restarts.

Configure the interface once and return to your preferred arrangement the next time you launch the IDE.

### 7. Themes and Appearance

PyxisIDE includes **16 custom themes**, offering different visual styles for different preferences.

- **Pyxis Midnight:** The signature PyxisIDE theme.
- **Dark themes:** Designed for users who prefer darker interfaces.
- **Light themes:** For a brighter development environment.
- **Gradient-inspired themes:** Alternative visual styles for a more personalized workspace.
- **System theme synchronization:** Follow the system appearance where supported.

Switch between available themes to make the IDE feel like your own workspace.

### 8. Navigation and Code Utilities

PyxisIDE includes practical editing and navigation tools to make working with source code easier.

- Line numbers and current-line highlighting.
- Automatic indentation.
- Code folding.
- Find and replace.
- Jump-to-line navigation.
- Syntax highlighting.
- Keyboard shortcuts for frequently used actions.
- Variable inspection through hover interactions, where supported.
- Automatic saving of editor changes.

PyxisIDE prioritizes a straightforward editing workflow rather than relying on a large autocomplete or code-suggestion system.

### 9. Automatic Saving

PyxisIDE includes automatic saving to reduce the risk of losing ordinary editing changes.

The saving mechanism also retries when a save operation fails.

Automatic saving is intended to make everyday editing more convenient. It should not be treated as a substitute for version control, backups, or testing recovery behavior after an unexpected shutdown.

### 10. Integrated Help and Application Information

PyxisIDE includes an **About Pyxis** section accessible through its help interface.

It identifies the creator of the project:

**Creator:** Faidul Islam

The application also includes its project copyright notice.

---

## ⌨️ Keyboard Shortcuts

PyxisIDE provides keyboard shortcuts for common editing and navigation tasks.

| Shortcut | Action |
|---|---|
| `F5` | Run the current program |
| `Ctrl + F` | Find text |
| `Ctrl + G` | Jump to a specific line |
| `Ctrl + S` | Save the current file |
| `Ctrl + Shift + S` | Save As |
| `Ctrl + B` | Open the native file explorer |

Additional shortcuts may be available within the application.

---

## 📥 Download

### Get PyxisIDE for Windows

PyxisIDE is distributed as a standalone Windows executable. The packaged application is approximately **550 MB**.

Because the executable exceeds GitHub's standard file-size limit for regular repository files, the binary is hosted externally.

<p align="center">
  <a href="https://drive.google.com/file/d/1bOvG19Ga3R_XmVkFkXfFt4npBk3zrPlM/view?usp=sharing">
    <img src="https://img.shields.io/badge/Download-PyxisIDE%20for%20Windows-2EA44F?style=for-the-badge&logo=google-drive&logoColor=white" alt="Download PyxisIDE">
  </a>
</p>

<p align="center">
  <strong>Replace the download link above with your actual Google Drive sharing link.</strong>
</p>

**Download instructions**

1. Open the download link above.
2. Download the PyxisIDE executable.
3. If Google Drive displays a large-file warning, follow its instructions to continue downloading.
4. Once the download finishes, locate the executable on your computer.
5. Launch PyxisIDE and begin coding.

**Important:** The executable is packaged to simplify installation, but exact runtime independence depends on which interpreters, compilers, and supporting components are bundled. Test the application on a clean Windows installation before claiming that no external runtimes are ever required.

Only download the executable from a source you trust.

---

## 🚀 Getting Started

### Requirements

- A Windows computer compatible with the packaged application.
- Sufficient free disk space for the approximately 550 MB download and its runtime files.
- Permission to launch the downloaded executable.

The application is intended to simplify setup through its packaged distribution. Compatibility with clean systems and the availability of all required language toolchains should be verified against the actual release.

### First Launch

1. Download and launch PyxisIDE.
2. Choose **New File** to start coding, or use **Open File** to load an existing source file.
3. Alternatively, open a project directory through the project explorer.
4. Write or edit your source code.
5. Press `F5` to run the current program.
6. View output and execution messages in the output panel.
7. Use the Stop control when you need to terminate a running program.

### Working with Projects

For projects containing multiple source files:

1. Open the project's directory.
2. Select the required source file from the project explorer.
3. Open related files in separate editor tabs.
4. Edit and save the files as needed.
5. Run the intended source file from the IDE.

By default, the working directory follows the directory containing the script. This can help programs locate nearby resources without requiring a separate working-directory configuration.

### Returning to Your Workspace

PyxisIDE remembers supported interface preferences, including the customized panel arrangement and theme.

The application opens its start screen rather than automatically reopening the previous project. Select your desired file or directory to begin a new session.

---

## 🖼️ Screenshots

See PyxisIDE in action.

> Add genuine screenshots of the application to the repository's `assets/` directory, then update the image paths below.

### Main Interface

![PyxisIDE Main Interface](assets/pyxiside-main.png)

*The main development environment, including the code editor and integrated workspace.*

### Project Explorer and Multi-Tab Editing

![PyxisIDE Project Explorer](assets/pyxiside-project-explorer.png)

*Navigate project files and work across multiple open source files.*

### Execution and Output

![PyxisIDE Execution Panel](assets/pyxiside-execution.png)

*Run programs and inspect their output without leaving the IDE.*

### Theme Gallery

![PyxisIDE Themes](assets/pyxiside-themes.png)

*Explore PyxisIDE's custom themes and personalize the interface.*

### Custom Workspace Layout

![PyxisIDE Custom Workspace](assets/pyxiside-workspace.png)

*Arrange supported panels to suit your development workflow.*

---

## 🏗️ Design Philosophy

PyxisIDE is built around several practical ideas.

**One environment. Multiple languages.**  
A developer should be able to work with multiple supported languages without maintaining a separate editor for each one.

**Customization without unnecessary complexity.**  
The workspace should adapt to different working styles while remaining approachable.

**Execution belongs close to the editor.**  
Running a program, reviewing output, and stopping execution should be straightforward actions within the same environment.

**Useful features over feature overload.**  
Tools such as multi-tab editing, syntax highlighting, code folding, automatic saving, and integrated terminal access are intended to improve everyday development.

**Distribution should be convenient.**  
A packaged executable can reduce setup friction for users who want to try the application without manually assembling the development environment.

---

## ⚙️ Technical Overview

PyxisIDE is a Windows desktop application developed in Python and packaged into a large executable for distribution.

| Component | Description |
|---|---|
| Application | PyxisIDE desktop IDE |
| Primary implementation language | Python |
| Supported source languages | Python, Java, C# |
| Code editing | Multi-tab source editor |
| File management | Integrated project explorer |
| Execution | Custom execution engine |
| Output | Integrated output panel |
| Terminal | Native Windows command-shell access |
| Interface | Customizable panel-based workspace |
| Appearance | 16 custom themes and system synchronization |
| Distribution | Packaged Windows executable |

The execution and compilation workflow depends on the actual runtime components included in the distribution. This section describes the application's design at a high level and does not imply that every external toolchain is embedded in a single executable binary.

---

## 🧪 Testing and Reliability

PyxisIDE has been tested through development-focused checks, including program execution, interactive input, and high-volume console output.

One recorded benchmark involved printing **10,000 lines in approximately 0.94 seconds** under the tested conditions.

Performance can vary depending on the computer, program, console rendering, and how execution time is measured. This result should be treated as a development benchmark rather than a universal performance guarantee.

Testing is an ongoing process. Additional testing on different Windows systems, especially systems without preinstalled development toolchains, is valuable for verifying compatibility and distribution behavior.

---

## 🛣️ Future Development

PyxisIDE is a personal software project that can continue to evolve as new ideas and improvements are developed.

Potential future directions include:

- Expanded editing and navigation tools.
- More detailed diagnostics and error presentation.
- Improved project management.
- Additional execution and debugging utilities.
- More extensive reliability and compatibility testing.
- Further improvements to the interface and customization system.

These are possible areas for future work, not promises that specific features are already implemented or scheduled for release.

---

## 👨‍💻 About the Project

PyxisIDE was created by **Faidul Islam** as a personal development project focused on building a customizable, multi-language desktop IDE.

The project brings together code editing, project navigation, execution management, terminal access, and interface customization in one application.

PyxisIDE reflects an interest in software development, practical tooling, and creating applications that solve real workflow problems.

### Creator

**Faidul Islam**

- GitHub: [@FrustratedFI](https://github.com/FrustratedFI)
- Portfolio: [faidulislam](https://frustratedfi.github.io/faidulislam)

---

## 📜 License and Copyright

**Copyright © 2026 Faidul Islam. All rights reserved.**

Unless a separate license is explicitly provided in this repository, the source code and project materials should be treated as reserved by the creator. No permission to redistribute, modify, or commercially use the project is granted by this README alone.

If you intend to publish the source code for public reuse, consider adding a dedicated `LICENSE` file that clearly states the permissions and restrictions.

---

<p align="center">
  <strong>PyxisIDE</strong>
  <br>
  Built with curiosity. Designed for development.
  <br><br>
  <sub>Created by Faidul Islam · © 2026</sub>
</p>
