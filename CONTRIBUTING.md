# Contributing to Incredible India Explorer 🇮🇳

Thank you for your interest in contributing to **Incredible India Explorer**! We welcome contributions from developers of all experience levels. Whether you're fixing bugs, improving the UI, creating educational games, or adding new explorer modules, your contributions help make this project better for everyone.

---

# Table of Contents

* Code of Conduct
* Getting Started
* Development Workflow
* Project Structure
* Creating a New Feature
* Coding Standards
* Pull Request Guidelines
* Commit Message Convention
* Reporting Issues

---

# Code of Conduct

Please be respectful and collaborative. By participating in this project, you agree to follow our Code of Conduct and help maintain a welcoming environment for everyone.

---

# Getting Started

1. Fork this repository.
2. Clone your fork.

```bash
git clone https://github.com/your-username/Incredible-India-Explorer.git
```

3. Navigate into the project.

```bash
cd Incredible-India-Explorer
```

4. Create a new branch.

```bash
git checkout -b feat/your-feature-name
```

5. Open the project using your preferred editor.

Since this project uses **HTML, CSS, and JavaScript**, no build tools or package installation are required.

---

# Development Workflow

1. Pick an issue assigned to you.
2. Create a new branch from `main`.
3. Develop your feature.
4. Test thoroughly.
5. Commit your changes.
6. Push your branch.
7. Open a Pull Request.

---

# 📁 Project Structure

The project follows a **feature-based architecture**.

Every feature is self-contained inside its own folder under the **frontend** directory.

```
Incredible-India-Explorer/
│
├── frontend/
│   ├── feature-name/
│   │   ├── index.html
│   │   ├── style.css
│   │   └── script.js
│   │
│   ├── another-feature/
│   │   ├── index.html
│   │   ├── style.css
│   │   └── script.js
│   │
│   └── ...
│
├── assets/
├── .github/
├── README.md
└── CONTRIBUTING.md
```

---

# 🚨 Creating a New Feature

Every new feature **must** follow the project structure.

## Step 1

Create a folder inside `frontend`.

Example

```
frontend/state-capital-game/
```

---

## Step 2

Inside that folder create:

```
index.html
style.css
script.js
```

Final structure:

```
frontend/
└── state-capital-game/
    ├── index.html
    ├── style.css
    └── script.js
```

---

## ❌ Do NOT

Do **not** create files like

```
frontend/game.html
frontend/style.css
frontend/script.js
```

or

```
frontend/random.js
frontend/page.css
```

Loose HTML, CSS, or JavaScript files inside the `frontend` directory are **not allowed**.

---

## Feature Folder Naming

Use **kebab-case**.

✅ Good

```
river-origin-challenge
state-jigsaw
metro-master
temple-architect
```

❌ Bad

```
RiverGame
River Game
MyFeature
test123
```

---

# Coding Standards

## HTML

* Use semantic HTML5 elements.
* Maintain proper indentation.
* Include meaningful page titles.
* Add `alt` text for images.
* Use ARIA attributes where appropriate.

---

## CSS

* Keep styles inside the feature's own `style.css`.
* Write responsive layouts.
* Use reusable CSS classes.
* Avoid unnecessary inline styles.
* Maintain consistent spacing and formatting.

---

## JavaScript

* Use vanilla JavaScript only.
* Prefer `const` and `let`.
* Write modular and readable code.
* Comment complex logic where necessary.
* Avoid polluting the global namespace.

---

# Responsive Design

Your feature should work properly on:

* Desktop
* Laptop
* Tablet
* Mobile devices

Test responsive layouts before submitting.

---

# Accessibility

Please ensure:

* Keyboard navigation works.
* Buttons have descriptive labels.
* Images include `alt` attributes.
* Color contrast is readable.
* Forms are accessible.

---

# Pull Request Guidelines

Before opening a Pull Request:

* Your feature follows the folder structure.
* No console errors.
* Responsive on different screen sizes.
* Existing functionality is not broken.
* Code is clean and properly formatted.
* Documentation is updated if required.

Please keep PRs focused on **one issue only**.

---

# Commit Message Convention

We follow Conventional Commits.

Examples:

```
feat: add metro master game

fix: correct state map rendering

docs: update contributing guide

style: improve navbar responsiveness

refactor: organize frontend feature folders
```

---

# Reporting Bugs

When reporting bugs, include:

* Steps to reproduce
* Expected behavior
* Actual behavior
* Browser information
* Screenshots (if applicable)

---

# Before Submitting

Please verify the following:

* Feature is inside its own folder in `frontend/`
* Folder contains:

  * `index.html`
  * `style.css`
  * `script.js`
* Code is responsive
* No console errors
* Existing pages continue to work
* Follows project coding standards

---

# Need Help?

If you have questions about an issue or implementation, feel free to ask in the issue discussion before starting work.

Happy Contributing! 🚀🇮🇳

