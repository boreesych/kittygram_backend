# Kittygram Backend

This repository is an example assignment for students: implement a backend for a Single Page Application (SPA).

## How to run the project

Clone the repository and navigate to it in your terminal:

```
git clone https://github.com/boreesych/kittygram_backend.git
cd kittygram_backend
```

Create and activate a virtual environment:

```
python3 -m venv env
source env/bin/activate
python3 -m pip install --upgrade pip
```

Install dependencies from `requirements.txt`:

```
pip install -r requirements.txt
```

Apply migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```

---

> **Note:**  
> This project is for educational purposes. Students are expected to implement the backend logic, models, and API for the SPA