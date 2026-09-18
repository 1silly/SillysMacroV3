# SillysMacroV3

A lightweight and customizable macro application built for Windows, featuring a modern interface, configurable keybinds, and multiple automation options.

> **SillysMacroV3** is currently under development. Features and functionality may change between releases.

## ✨ Features

* 🎮 **Custom Keybinds** — Configure your preferred keys for different actions.
* ⚡ **Low-Latency Macros** — Configure precise delays in milliseconds.
* 🎯 **Drag Edit Macro** — Customizable timing for edit actions.
* 🔫 **Shotgun Support** — Configure shotgun-related automation.
* 🖱️ **Pickup Macro** — Automate pickup actions with configurable settings.
* 🏃 **Auto Sprint** — Optional automatic sprint functionality.
* ⛏️ **Auto Pickaxe** — Optional automatic pickaxe functionality.
* 🎛️ **Drag Edit Settings** — Fine-tune timing and behavior.
* 🖥️ **Modern UI** — Dark gaming-inspired interface designed for easy navigation.
* 💾 **Persistent Settings** — Save your configuration for future sessions.
* 📦 **Standalone Build** — Can be packaged into a standalone Windows executable.

## 🖥️ Interface

The application includes several sections:

| Section         | Description                         |
| --------------- | ----------------------------------- |
| **Keybinds**    | Configure macro keys and shortcuts  |
| **Drag Edit**   | Configure drag-edit timing          |
| **Double Edit** | Configure double-edit functionality |
| **Pickup**      | Configure pickup automation         |
| **Shotgun**     | Configure shotgun-related settings  |
| **Credits**     | Project and developer information   |

## ⚙️ Configuration

SillysMacroV3 allows you to configure individual macro settings directly from the application.

Example:

```text
Drag Edit
├── Keybind
├── Delay
├── Enable / Disable
└── Additional options

Auto Sprint
└── Enable / Disable

Auto Pickaxe
└── Enable / Disable
```

### Timing

Macro delays can be configured in milliseconds.

For example:

```text
5 ms
10 ms
15 ms
20 ms
```

Lower values may result in faster actions, while higher values introduce additional delay.

## 💻 Requirements

### Operating System

* Windows 10
* Windows 11

### Development

If you're running the source code directly:

* Python 3.10+
* pip
* Windows

Check your Python installation:

```powershell
python --version
```

## 🚀 Installation

### Option 1 — Release

Download the latest release from the repository's **Releases** section.

Extract the downloaded files and launch:

```text
SillysMacroV3.exe
```

### Option 2 — Run From Source

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/SillysMacroV3.git
```

Enter the project directory:

```bash
cd SillysMacroV3
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python macro.py
```

## 🔨 Building

The project can be packaged into a standalone executable using PyInstaller.

Install PyInstaller:

```bash
pip install pyinstaller
```

Build:

```bash
pyinstaller --onefile --noconsole macro.py
```

The compiled executable will be located inside:

```text
dist/
```

Example:

```text
SillysMacroV3/
├── macro.py
├── requirements.txt
├── README.md
├── assets/
└── dist/
    └── macro.exe
```

## 📁 Project Structure

```text
SillysMacroV3/
│
├── macro.py
├── requirements.txt
├── README.md
│
├── assets/
│   ├── icons/
│   └── images/
│
└── dist/
    └── SillysMacroV3.exe
```

## 🎨 Design

SillysMacroV3 uses a dark, minimal gaming-oriented design with a focus on:

* Fast navigation
* Clear controls
* Minimal visual clutter
* Easy-to-understand settings
* Configurable macro timing

## 🛠️ Development

Want to contribute?

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/my-feature
```

3. Make your changes.
4. Test your changes locally.
5. Commit your changes.

```bash
git commit -m "Add my feature"
```

6. Push your branch.

```bash
git push origin feature/my-feature
```

7. Open a Pull Request.

## 🐛 Bug Reports

If you find a bug, please open an issue and include:

* Windows version
* SillysMacroV3 version
* Steps to reproduce the issue
* What you expected to happen
* What actually happened
* Relevant error messages or screenshots

Example:

```text
Version: 3.0.0
OS: Windows 10 22H2

Issue:
The Drag Edit macro does not activate when pressing the configured key.

Steps:
1. Open SillysMacroV3
2. Go to Drag Edit
3. Set the keybind
4. Enable the macro
5. Press the configured key
```

## 📋 Roadmap

* [x] Modernized UI
* [x] Keybind system
* [x] Drag Edit settings
* [x] Configurable timing
* [x] Auto Sprint
* [x] Auto Pickaxe
* [ ] Improved settings system
* [ ] Configuration profiles
* [ ] Import / export configurations
* [ ] Improved performance
* [ ] More customization options
* [ ] Additional macro modules

## 🔒 Security & Privacy

SillysMacroV3 should not require unnecessary personal information to operate.

Always download releases from trusted project sources and review third-party builds before running them.

## ⚠️ Disclaimer

SillysMacroV3 is provided for educational and personal-use purposes.

The developers are not responsible for account restrictions, bans, data loss, system issues, or other consequences resulting from the use of the software.

Users are responsible for following the rules and terms of the applications or games they use the software with.

## 📜 License

This project is currently distributed under the license specified in the repository.

If a license has not yet been added, all rights are reserved by the copyright holder.

## 👤 Credits

**SillysMacroV3**

Developed by **Sillys**

Built with:

* Python
* PyInstaller
* Windows

---

### ⭐ Support the Project

If you find SillysMacroV3 useful, consider giving the repository a ⭐ on GitHub.

**SillysMacroV3 — Simple. Fast. Configurable.**
