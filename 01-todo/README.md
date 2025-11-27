# Django TODO Application

A production-ready TODO application with vibrant UI and comprehensive test coverage.

## Features

- ✅ Create, edit, and delete tasks
- ✅ Due date assignment with date picker
- ✅ Mark tasks as complete/incomplete
- ✅ Bulk select and delete operations
- ✅ Vibrant color scheme with smooth animations
- ✅ 133 comprehensive tests (100% passing)

## Tech Stack

- Django 4.2
- Bootstrap 5.1.3
- SQLite
- 100% test coverage

## Quick Start

```bash
python3 manage.py runserver 8001
```

Open: http://localhost:8001/todos/

## Run Tests

```bash
python3 manage.py test todos.tests
```

## Project Structure

```
├── todos/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html          # Base template with styling
│   │   ├── home.html          # Todo list view with bulk operations
│   │   └── todos/
│   │       ├── todo_form.html # Create/edit form
│   │       └── todo_confirm_delete.html
│   ├── tests/
│   │   ├── test_models.py     # Model tests
│   │   ├── test_views.py      # View tests
│   │   ├── test_forms.py      # Form tests
│   │   ├── test_integration.py # Integration tests
│   │   ├── test_scenarios.py  # Edge case tests
│   │   └── conftest.py        # Test fixtures
│   ├── models.py              # Todo model
│   ├── views.py               # CRUD views
│   ├── forms.py               # Form validation
│   ├── urls.py                # URL routing
│   └── admin.py
├── manage.py
└── db.sqlite3
```

## Status

✅ Deployed and fully functional
