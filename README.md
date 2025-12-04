# Car Management System (CLI)

Simple command-line Car Management System storing data in `cars.json`.

Features:
- Add new car
- View all cars
- Search by ID
- Update car details
- Delete car
- Change car status (Available / Sold / Maintenance)
- Summary report

Requirements:
- Python 3.8+
This project has been upgraded to use SQLAlchemy ORM and a Click-based CLI.

Requirements:
- Python 3.8+
- Pipenv to manage the virtual environment (Pipfile included)

Quick start:

Create the environment and install dependencies:
```bash
pipenv install --dev
pipenv shell
```

Initialize the database and try the CLI:
```bash
python3 main.py init
python3 main.py add-car
python3 main.py list-cars
python3 main.py summary
```

Database file: `cars.db` (SQLite by default). To override, set `CARS_DB` env var.

Future: GUI, authentication, analytics.
# phase-3-project
