# 7–10 Day Python API Testing, Logging & Debugging Roadmap 🎯

**Goal**: Master API testing with Python's `requests`, `pytest`, structured logging, and debugging.

**Free APIs for practice**:  
- <a href="https://jsonplaceholder.typicode.com" target="_blank">JSONPlaceholder</a>  
- <a href="https://reqres.in" target="_blank">Reqres</a>  

**YouTube Playlist**:  
- <a href="https://www.youtube.com/watch?v=-Lk-_2saFk8" target="_blank">Python Requests API Automation with pytest</a>  
- <a href="https://www.youtube.com/watch?v=cHYq1MRoyI0" target="_blank">Pytest Tutorial – How to Test Python Code</a>  
- <a href="https://www.youtube.com/watch?v=dBK2e_DuZVs" target="_blank">Build a Robust API Automation Framework with Python</a>  

---

## 📅 Day-by-Day Checklist with Resources & Celebrations

---

### **Day 1: Requests Basics**
- [ ] Install `requests` (`pip install requests`)
- [ ] Learn <a href="https://requests.readthedocs.io/en/latest/user/quickstart/" target="_blank">GET, POST, PUT, DELETE</a>
- [ ] Pass <a href="https://realpython.com/python-requests/" target="_blank">headers, query params, JSON body</a>
- [ ] Call <a href="https://jsonplaceholder.typicode.com" target="_blank">free APIs</a> & print status + JSON
- [ ] Watch: <a href="https://www.youtube.com/watch?v=-Lk-_2saFk8" target="_blank">Python Requests API Automation with pytest</a>

✅ **If all checked:** 🎉 *Congrats! You can now make any kind of HTTP request with Python and handle responses confidently!*

---

### **Day 2: Pytest Basics**
- [ ] Install `pytest` (`pip install pytest`)
- [ ] Learn <a href="https://docs.pytest.org/en/stable/getting-started.html" target="_blank">test discovery</a>
- [ ] Run with `pytest -v`
- [ ] Use `assert` for validation
- [ ] Watch: <a href="https://www.youtube.com/watch?v=cHYq1MRoyI0" target="_blank">Pytest Tutorial – How to Test Python Code</a>

✅ **If all checked:** 🎉 *You now know how to set up and run tests with pytest, and validate API responses like a pro!*

---

### **Day 3: Writing API Tests**
- [ ] Create a GET test for `/posts`
- [ ] Create a POST test for `/posts`
- [ ] Validate status code + JSON fields
- [ ] Use variables for URLs to avoid repetition  
📚 **Reference**: <a href="https://realpython.com/pytest-python-testing/" target="_blank">Effective Python Testing With Pytest</a>

✅ **If all checked:** 🎉 *Boom! You can now write functional API tests that ensure endpoints work as expected!*

---

### **Day 4: Pytest Fixtures**
- [ ] Learn <a href="https://docs.pytest.org/en/stable/how-to/fixtures.html" target="_blank">what fixtures are</a>
- [ ] Create fixture for base URL
- [ ] Use fixture in multiple test functions
- [ ] Explore fixture scope (`function`, `module`)  
📚 **Extra**: <a href="https://www.tutorialspoint.com/pytest/pytest_fixtures.htm" target="_blank">Pytest Fixtures Tutorial</a>

✅ **If all checked:** 🎉 *Great! You can now write reusable test setups with fixtures, saving time and avoiding repetition!*

---

### **Day 5: Import/Export in Python**
- [ ] Learn <a href="https://docs.python.org/3/tutorial/modules.html" target="_blank">modules & imports</a>
- [ ] Read <a href="https://www.programiz.com/python-programming/modules" target="_blank">Python Modules & Packages</a>
- [ ] Create `utils.py` with helper functions
- [ ] Import helpers into test files

✅ **If all checked:** 🎉 *Nice! You can now organize your code into reusable modules for cleaner, maintainable projects!*

---

### **Day 6: Logging with structlog**
- [ ] Install `structlog` (`pip install structlog`)
- [ ] Configure <a href="https://www.structlog.org/en/stable/getting-started.html" target="_blank">basic structured logging</a>
- [ ] Add logs for request & response
- [ ] Check logs in console  
📚 **Extra**: <a href="https://www.robustperception.io/a-brief-introduction-to-structlog" target="_blank">Intro to Structlog</a>

✅ **If all checked:** 🎉 *Awesome! You can now log requests and responses in a structured format, making debugging much easier!*

---

### **Day 7: Debugging Basics**
- [ ] Use `print()` and logger for quick checks
- [ ] Use <a href="https://docs.python.org/3/library/pdb.html" target="_blank">pdb debugger</a>
- [ ] Run with `pytest -s` to see print/logs
- [ ] Try IDE breakpoints  
📚 **Extra**: <a href="https://realpython.com/python-debugging-pdb/" target="_blank">Debugging with Pdb</a>  
📚 **PyCharm Debugging**: <a href="https://www.jetbrains.com/help/pycharm/debugging-code.html" target="_blank">JetBrains Debugger Tutorial</a>

✅ **If all checked:** 🎉 *Fantastic! You can now debug Python code interactively and track down tricky bugs with ease!*

---

### **Days 8–9: Mini Project**
- [ ] Choose 3–4 endpoints from a <a href="https://github.com/public-apis/public-apis" target="_blank">public API list</a>
- [ ] Write tests using fixtures & logging
- [ ] Add intentional failure for debugging practice
- [ ] Watch: <a href="https://www.youtube.com/watch?v=dBK2e_DuZVs" target="_blank">Build a Robust API Automation Framework with Python</a>

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
