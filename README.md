# 🖼 Templates for the Secure Online Exam System
This folder contains all HTML templates used in the Django-based online exam platform.
## 🎨 Design Notes

- All templates extend `base.html`, which includes Bootstrap 5 styling and dynamic nav links.
- Role checks (`user.role == 'admin'`) are used in templates to conditionally show content.
- CSRF tokens and Django form rendering conventions are used throughout.
- Minimal JS usage — ideal for progressive enhancement or JS-based upgrades later.

## 🔗 Usage

Templates are automatically loaded by the views defined in:

- `exams/views.py`
- `results/views.py`
- `accounts/views.py`

