# 📜 Python, Pytest & API Testing Commands Reference

A categorized list of commands and code snippets for quick reference while working on API testing, logging, and debugging.

---

## 📦 Python & Package Management

### Install a package
```bash
pip install package_name
```
Installs a package from PyPI.

### Install multiple packages from a file
```bash
pip install -r requirements.txt
```
Installs all dependencies listed in `requirements.txt`.

### Upgrade a package
```bash
pip install --upgrade package_name
```
Updates the package to its latest version.

### Check installed packages
```bash
pip list
```
Displays a list of all installed packages.

---

## 🌐 Requests (API Calls)

### Basic GET request
```python
import requests
r = requests.get("https://jsonplaceholder.typicode.com/posts/1")
print(r.status_code, r.json())
```
Sends a GET request and prints status code & response.

### POST request with JSON
```python
import requests
payload = {"name": "John", "age": 30}
r = requests.post("https://reqres.in/api/users", json=payload)
print(r.status_code, r.json())
```
Sends data to the server in JSON format.

---

## 🧪 Pytest Commands

### Run all tests in current directory
```bash
pytest
```

### Run tests with verbose output
```bash
pytest -v
```
Shows detailed test names and results.

### Show `print()` and log outputs during tests
```bash
pytest -s
```

### Run tests from a specific file
```bash
pytest test_file.py
```

### Run a specific test function
```bash
pytest test_file.py::test_function_name
```

### Drop into debugger on failure
```bash
pytest --pdb
```

---

## 🐞 Debugging

### Pause execution and inspect variables
```python
import pdb; pdb.set_trace()
```

### Run pytest with debugger enabled
```bash
pytest -s --pdb
```

#### Common `pdb` commands:
- `c` → Continue execution  
- `s` → Step into function  
- `n` → Step to next line  
- `p variable_name` → Print variable value  
- `q` → Quit debugger  

---

## 🗂 Import & Export

### Import specific function from another file
```python
from utils import my_function
```

### Import multiple items
```python
from utils import func1, func2
```

### Import module as alias
```python
import requests as req
```

---

## 📜 Logging

### Basic logging setup
```python
import logging
logging.basicConfig(level=logging.INFO)
logging.info("This is a log message")
```
Sets up basic logging and prints an INFO-level message.

### Structlog example
```python
import structlog
log = structlog.get_logger()
log.info("event", key="value")
```
Logs structured data for better readability and filtering.

---

## 🔗 Useful Public APIs for Practice
- [JSONPlaceholder](https://jsonplaceholder.typicode.com) → Fake REST API for testing  
- [Reqres](https://reqres.in) → Fake API for learning HTTP methods  
- [Swagger Petstore](https://petstore.swagger.io) → Example API with documentation  
- [Public APIs List](https://github.com/public-apis/public-apis) → Collection of free APIs

---
