# 🐍 Python CI App with GitHub Actions

This is a basic Python project with an automated **CI (Continuous Integration)** pipeline using **GitHub Actions**. It demonstrates setting up a DevOps pipeline from scratch, including:

- Dependency installation
- Linting with `flake8`
- Formatting check with `black`
- Unit testing with `pytest`

---

## 📁 Project Structure

```bash
.
├── app.py                   # Simple Python application logic
├── test_app.py              # Unit tests for the app
├── requirements.txt         # Python dependencies
└── .github/
    └── workflows/
        └── python-ci.yml    # GitHub Actions CI workflow
