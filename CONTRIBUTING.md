# 🤝 Contributing to Bolt

First off, thank you for taking the time to contribute to **Bolt**! Whether you're here to fix a bug, improve documentation, or build a new feature, we welcome your support.

This guide will help you get started with contributing to our projects.

---

## 📦 Repositories

Bolt is composed of several components. Please make sure you're working in the correct repository:

- [`bolt-server`](https://github.com/bolt-host/bolt-server): Core server software and sandbox runtime
- [`bolt-cli`](https://github.com/bolt-host/bolt-cli): Command-line interface
- [`bolt-docs`](https://github.com/bolt-host/bolt-docs): Documentation

---

## 🚧 How to Contribute

### 1. Fork the Repository

Create a fork of the repository you want to contribute to, and clone it locally.

```bash
git clone https://github.com/YOUR_USERNAME/bolt-server.git
cd bolt-server
````

### 2. Create a New Branch

Use a descriptive name that explains your change.

```bash
git checkout -b fix/memory-leak-in-sandbox
```

### 3. Make Your Changes

* Follow the project's coding conventions
* Write clear, concise commit messages
* If it's a bugfix, add a test if possible
* If it's a feature, document it clearly

### 4. Run Tests

Ensure all tests pass before submitting a pull request. If you're adding a new feature, include tests for it.

```bash
# Example (for Python)
pytest tests/
```

### 5. Submit a Pull Request

Go to your fork on GitHub and click **"New Pull Request"**.

* Describe what you’ve changed and why
* Reference any related issues (e.g. `Closes #42`)
* If it’s a work-in-progress, label it `[WIP]`

---

## 🧪 Code Standards

Each repo may have its own standards (see the repo’s README or `CONTRIBUTING.md`), but in general:

* **Languages**: Python (CLI & Server)
* **Style Guides**:

  * Python: [PEP8](https://peps.python.org/pep-0008/)

---

## 📚 Improving Documentation

We love documentation updates! You can:

* Fix typos or outdated content
* Write usage guides, examples, or tutorials
* Improve inline code comments

Documentation lives in:

* [`bolt-docs`](https://github.com/bolt-host/bolt-docs)
* `README.md` or `docs/` folders in each repo

---

## 🐞 Reporting Issues

If you encounter a bug or have a feature request:

* Use the issue templates in the appropriate repositories.
* Include steps to reproduce, logs, screenshots, or error messages
* For security issues, **please do not** open a public issue. Email us at [me@proplayer919.dev](mailto:me@proplayer919.dev) instead.

---

## 💬 Community & Help

* Ask questions or get help in [Discussions](https://github.com/bolt-host/.github/discussions)
* Be respectful — follow our [Code of Conduct](https://github.com/bolt-host/.github/blob/main/CODE_OF_CONDUCT.md)

---

## ✅ Checklist Before You Submit

* [ ] All tests pass
* [ ] Code follows style guidelines
* [ ] Docs updated (if applicable)
* [ ] PR description is clear and linked to issues

---

## 🧾 License

By contributing, you agree that your contributions will be licensed under the same license as the project: [MIT](https://opensource.org/licenses/MIT)

---

> Thank you again for helping make Bolt better! ⚡
