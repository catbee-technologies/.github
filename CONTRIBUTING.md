# Contributing to Catbee Technologies

Thank you for your interest in contributing to Catbee Technologies!  
We welcome improvements of all kinds — bug fixes, new features, performance enhancements, documentation updates, or general refinements across any of our open-source projects.

Please read the guidelines below to help ensure a smooth and effective contribution process.

---

## 🚀 How to Contribute

### 1. Fork & Clone the Repository

Most contributions begin by forking the target repository:

```sh
git clone https://github.com/catbee-technologies/<repo-name>.git
cd <repo-name>
```

### 2. Create a Feature Branch

Use a clear and consistent naming convention:

```
fix/issue-123
feature/add-retry-logic
refactor/logger-cleanup
docs/update-readme
test/improve-coverage
```

```sh
git checkout -b feature/add-retry-logic
```

### 3. Make Your Changes

- Keep changes **focused** and **atomic**.  
- Follow the existing project style and architecture.
- Add or update tests when applicable.
- Write clear and maintainable code (TypeScript preferred where applicable).
- For documentation changes, follow the repo’s formatting and structure.

### 4. Run Tests, Linting, and Build

Before committing:

```sh
npm install
npm run lint
npm test
npm run build
```

(Commands may vary by repository; check the project README.)

Ensure:

- No linting errors  
- All tests pass  
- The project builds successfully  

### 5. Commit Your Changes

Use clear, descriptive commit messages.  
We recommend **Conventional Commits**:

```
feat: add request timeout support
fix: correct cache expiration logic
refactor: simplify error handling
docs: update usage examples
chore: bump dependencies
```

### 6. Push & Open a Pull Request

```sh
git push origin feature/add-retry-logic
```

When opening a PR, include:

- A description of the change  
- The reasoning or problem it solves  
- Screenshots (if UI-related)  
- Links to relevant issues  

---

## 🐛 Reporting Issues

For any Catbee project:

- Search existing issues before opening a new one.
- Provide clear reproduction steps.
- Include environment details when relevant (Node.js version, OS, package versions).
- For security-related issues, **do not** open a public issue — see `SECURITY.md`.

---

## 🧪 Pull Request Review Process

PRs are reviewed for:

- Code clarity and maintainability  
- Test coverage and reliability  
- Consistent style and architecture  
- Performance considerations  
- Documentation completeness  
- Commit message quality  

We aim to review contributions within **1–3 business days**.

---

## 📜 Code of Conduct

All contributors must follow the Contributor Covenant Code of Conduct.  
By participating, you agree to uphold these standards.

Read the full Code of Conduct here:  
**[CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)**

Concerns or violations can be reported privately via:  
**hprasath.dev@gmail.com**

---

## 🙌 Thank You

We appreciate your time, effort, and contributions!  
Every PR, issue, and suggestion helps strengthen the Catbee ecosystem.

Welcome to the community
