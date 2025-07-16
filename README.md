🧭 tkaria11y

[![CodeFactor](https://www.codefactor.io/repository/github/stntg/tkaria11y/badge)](https://www.codefactor.io/repository/github/stntg/tkaria11y)

tkaria11y is a Python framework for building fully accessible Tkinter applications—offering ARIA-style metadata, automatic text-to-speech feedback, keyboard navigation, high-contrast theming, and dyslexic-friendly fonts.

Whether you're crafting GUIs for the visually impaired, dyslexic users, screen-reader users, or simply building inclusive software, tk-a11y gives you a robust set of tools with minimal boilerplate.

---

🚀 Features

- ✅ Accessible Widget Classes (e.g., AccessibleButton, AccessibleEntry)
- 🎙️ Text-to-Speech Feedback on focus and hover
- 🔍 ARIA-style metadata: accessible_name, role, description
- ⌨️ Logical keyboard navigation with <Tab> / <Shift-Tab>
- 🎨 High-contrast themes and OpenDyslexic font support
- 🧱 Dynamic widget factory for custom widgets
- 🧪 Runtime widget inspector with metadata overlay
- 🛠️ Type-stub generator for full IDE support
- 📦 Codemod migration CLI (coming soon)

---

📦 Installation

Install the stable release from PyPI:

`bash
pip install tk-a11y
`

Install optional dev tools (testing, type checking, stub generation):

`bash
pip install "tkaria11y[dev]"
`

---

🧪 Quickstart


🔍 Runtime Inspector

Press F2 to open the built-in accessibility inspector:

- Shows widget hierarchy and metadata
- Highlights currently focused widget
- Helps audit accessible names, roles, and navigation

---

🧰 Developer Tools

Generate Type Stubs

`bash
python scripts/generate_stubs.py
`

Creates stubs/widgets.pyi for type checkers and IDEs.

Run Tests

`bash
pytest
`

Lint & Format

`bash
black .
flake8 .
`

---

🧙‍♂️ Codemod (Coming Soon)

Automatically upgrade your Tkinter codebase to accessible widgets:

`bash
tka11y-migrate path/to/your/app.py --interactive
`

Supports auto-imports, accessible_name inference, and config-based overrides.

---

📚 Documentation

Documentation lives in the docs/ folder and is published at tk-a11y.readthedocs.io (coming soon).

---

🤝 Contributing

We welcome accessibility advocates, Tkinter hackers, and curious contributors of all skill levels.

- See CONTRIBUTING.md
- Run tests and generate stubs before submitting PRs
- Open issues for bugs, ideas, or widget requests
- Adhere to our Code of Conduct

---

📄 License

MIT © [Your Name]  
See LICENSE for details.

---

🙌 Acknowledgements

Inspired by ARIA specs, WCAG principles, open-source accessibility tooling, and the Python community’s commitment to inclusion.

---

🗺️ Roadmap

Want to see where we're headed? Check out ROADMAP.md.
