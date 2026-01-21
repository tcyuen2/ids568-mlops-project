# IDS568 MLOps Project

## Setup Instructions

1. Clone the repository:
```bash
   git clone https://github.com/tcyuen2/ids568-mlops-project.git
   cd ids568-mlops-project
```

2. Create and activate virtual environment:
```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
    pip install pytest pandas numpy scikit-learn
   pip freeze > requirements.txt
```

4. Run tests:
```bash
   pytest
```

## CI Status

![CI](https://github.com/tcyuen2/ids568-mlops-project/actions/workflows/ci.yml/badge.svg)

## Reproducibility

This project uses:
- **Pinned dependencies** in `requirements.txt` with exact versions
- **Virtual environment** for isolated Python packages
- **GitHub Actions CI** to verify the environment works on a clean machine
```

## Step 7: Create .gitignore

Create `.gitignore` in the root:
```
venv/
__pycache__/
*.pyc
.pytest_cache/