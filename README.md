# mlh-holiday-planner

## Installation

Make sure you have python3 and pip installed
Create and activate virtual environment using virtualenv
```bash
$ python -m venv python3-virtualenv
$ source python3-virtualenv/bin/activate
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all dependencies

```bash
pip install -r requirements.txt
```

## Usage


Create a .env file with the following line included: 
```bash
URL=localhost:5000
```
URL=localhost:5000


Start flask development server
```bash
$ export FLASK_ENV=development
$ flask run
```
