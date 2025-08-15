# 7–10 Day Python API Testing, Logging & Debugging Roadmap 🎯

**Goal**: Master API testing with Python's `requests`, `pytest`, structured logging, and debugging.

**Free APIs for practice**:  
- [JSONPlaceholder](https://jsonplaceholder.typicode.com)  
- [Reqres](https://reqres.in)  

**YouTube Playlist**:  
- [Python Requests API Automation with pytest](https://www.youtube.com/watch?v=-Lk-_2saFk8)  
- [Pytest Tutorial – How to Test Python Code](https://www.youtube.com/watch?v=cHYq1MRoyI0)  
- [Build a Robust API Automation Framework with Python](https://www.youtube.com/watch?v=dBK2e_DuZVs)  

---

## 📅 Day-by-Day Checklist with Resources & Celebrations

---

### **Day 1: Requests Basics**
- [ ] Install `requests` (`pip install requests`)
- [ ] Learn [GET, POST, PUT, DELETE](https://requests.readthedocs.io/en/latest/user/quickstart/)
- [ ] Pass [headers, query params, JSON body](https://realpython.com/python-requests/)
- [ ] Call [free APIs](https://jsonplaceholder.typicode.com) & print status + JSON
- [ ] Watch: [Python Requests API Automation with pytest](https://www.youtube.com/watch?v=-Lk-_2saFk8)

✅ **If all checked:** 🎉 *Congrats! You can now make any kind of HTTP request with Python and handle responses confidently!*

---

### **Day 2: Pytest Basics**
- [ ] Install `pytest` (`pip install pytest`)
- [ ] Learn [test discovery](https://docs.pytest.org/en/stable/getting-started.html)
- [ ] Run with `pytest -v`
- [ ] Use `assert` for validation
- [ ] Watch: [Pytest Tutorial – How to Test Python Code](https://www.youtube.com/watch?v=cHYq1MRoyI0)

✅ **If all checked:** 🎉 *You now know how to set up and run tests with pytest, and validate API responses like a pro!*

---

### **Day 3: Writing API Tests**
- [ ] Create a GET test for `/posts`
- [ ] Create a POST test for `/posts`
- [ ] Validate status code + JSON fields
- [ ] Use variables for URLs to avoid repetition  
📚 **Reference**: [Effective Python Testing With Pytest](https://realpython.com/pytest-python-testing/)

✅ **If all checked:** 🎉 *Boom! You can now write functional API tests that ensure endpoints work as expected!*

---

### **Day 4: Pytest Fixtures**
- [ ] Learn [what fixtures are](https://docs.pytest.org/en/stable/how-to/fixtures.html)
- [ ] Create fixture for base URL
- [ ] Use fixture in multiple test functions
- [ ] Explore fixture scope (`function`, `module`)  
📚 **Extra**: [Pytest Fixtures Tutorial](https://www.tutorialspoint.com/pytest/pytest_fixtures.htm)

✅ **If all checked:** 🎉 *Great! You can now write reusable test setups with fixtures, saving time and avoiding repetition!*

---

### **Day 5: Import/Export in Python**
- [ ] Learn [modules & imports](https://docs.python.org/3/tutorial/modules.html)
- [ ] Read [Python Modules & Packages](https://www.programiz.com/python-programming/modules)
- [ ] Create `utils.py` with helper functions
- [ ] Import helpers into test files

✅ **If all checked:** 🎉 *Nice! You can now organize your code into reusable modules for cleaner, maintainable projects!*

---

### **Day 6: Logging with structlog**
- [ ] Install `structlog` (`pip install structlog`)
- [ ] Configure [basic structured logging](https://www.structlog.org/en/stable/getting-started.html)
- [ ] Add logs for request & response
- [ ] Check logs in console  
📚 **Extra**: [Intro to Structlog](https://www.robustperception.io/a-brief-introduction-to-structlog)

✅ **If all checked:** 🎉 *Awesome! You can now log requests and responses in a structured format, making debugging much easier!*

---

### **Day 7: Debugging Basics**
- [ ] Use `print()` and logger for quick checks
- [ ] Use [pdb debugger](https://docs.python.org/3/library/pdb.html)
- [ ] Run with `pytest -s` to see print/logs
- [ ] Try IDE breakpoints  
📚 **Extra**: [Debugging with Pdb](https://realpython.com/python-debugging-pdb/)  
📚 **PyCharm Debugging**: [JetBrains Debugger Tutorial](https://www.jetbrains.com/help/pycharm/debugging-code.html)

✅ **If all checked:** 🎉 *Fantastic! You can now debug Python code interactively and track down tricky bugs with ease!*

---

### **Days 8–9: Mini Project**
- [ ] Choose 3–4 endpoints from a [public API list](https://github.com/public-apis/public-apis)
- [ ] Write tests using fixtures & logging
- [ ] Add intentional failure for debugging practice
- [ ] Watch: [Build a Robust API Automation Framework with Python](https://www.youtube.com/watch?v=dBK2e_DuZVs)

✅ **If all checked:** 🎉 *You’ve built your first complete API testing suite! You can now apply everything you’ve learned in real projects!*

---

### **Day 10: Review & Polish**
- [ ] Review weak areas
- [ ] Add `pytest.mark.parametrize` (optional)
- [ ] Ensure fixtures are reusable
- [ ] Clean and push project to GitHub

✅ **If all checked:** 🎉 *You’ve officially mastered Python API testing basics with logging and debugging — job ready!*

---

## 📝 Final Tips
- Run tests daily for retention  
- Break things intentionally to improve debugging skills  
- Use Git for version control  
- Keep sessions short but consistent