# {{ cookiecutter.project_name }}

Author: {{ cookiecutter.author_name }}

## 🚀 Setup
```bash
conda create -n {{ cookiecutter.repo_name }} python={{ cookiecutter.python_version }} -y
conda activate {{ cookiecutter.repo_name }}
pip install -r requirements.txt