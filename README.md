# fpx

**fpx** (Free Pascal eXecutor) is a modern **Command Line Interface (CLI)** built to automate common tasks in **Free Pascal** development, especially in integrated environments like **Visual Studio Code**.

This is the **beginning of the project**, and our goal is to provide a powerful yet simple tool inspired by package managers like `npm`, `yarn`, and `cargo`, but tailored to the **Pascal/FPC ecosystem**.

---

## 🔧 Objective

Provide a CLI that allows Pascal developers to:

- Quickly initialize new Pascal projects
- Compile Free Pascal code easily
- Automate build and deploy processes
- Easily integrate with modern editors like VS Code
- Have a unified standard for project automation (build/test/deploy/lint/etc)

---

## 🚀 Key Features (planned)

| Command       | Description |
|---------------|-------------|
| `fpx init`    | Initializes a new Pascal project with folder structure and basic files |
| `fpx build`   | Compiles the project for the current operating system |
| `fpx run`     | Runs the binary after build |
| `fpx clean`   | Removes temporary files and compiled binaries |
| `fpx deploy`  | Deploys the binary or generates a package for distribution |
| `fpx test`    | Runs automated tests (coming soon) |
| `fpx install` | Installs dependencies from external libraries (planned) |
| `fpx config`  | Configures global or project-specific variables and options |
| `fpx help`    | Shows general help or command-specific help |

---

## 💡 Highlights

- Compatible with **Free Pascal** and **Lazarus**
- Designed for **VS Code** and integrated terminals
- Open-source and extensible
- Supports **cross-compilation** for Linux, Windows, and macOS
- Future support for containers, CI/CD, templates, live reload, and graphical libraries

---

## 📦 Requirements

- [Free Pascal Compiler (FPC)](https://www.freepascal.org/)
- [VS Code](https://code.visualstudio.com/) with Pascal extension
- OS: Windows, Linux, or macOS

---

## 🛠️ Project Status

🚧 Project in early stage.  
We are structuring internal modules, commands, and the CLI engine.

Follow the updates and contribute with suggestions, tests, and ideas!

---

## 📂 Expected Initial Structure

```
my-app/
├── src/
│   └── main.pas
├── fpx.toml         ← Project configuration file
├── bin/             ← Compiled binaries
└── tests/           ← Scripts and automated tests
```

---

## 🤝 Contributions

We welcome suggestions, pull requests, improvements, and testing!  
You can help with:

- New command ideas
- Automation scripts
- Documentation
- Multi-platform testing

---

## 📄 License

This project will be licensed under the **MIT License** (initial proposal).

---

## ✨ Author

Created by **@marcosnielsen**  
Inspired by the legacy of **Blaise Pascal**, and modern automation tools.

---
