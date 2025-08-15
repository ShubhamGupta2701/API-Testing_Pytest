# 7–10 Day Python API Testing, Logging & Debugging Roadmap 🎯

**Goal**: Master API testing with Python's `requests`, `pytest`, structured logging, and debugging.

**Free APIs for practice**:  
- https://jsonplaceholder.typicode.com  
- https://reqres.in  

**YouTube Playlist**:  
- [Python Requests API Automation with pytest](https://www.youtube.com/watch?v=-Lk-_2saFk8)  
- [Pytest Tutorial – How to Test Python Code](https://www.youtube.com/watch?v=cHYq1MRoyI0)  
- [Build a Robust API Automation Framework with Python](https://www.youtube.com/watch?v=dBK2e_DuZVs)  

---

## 📅 Day-by-Day Checklist with Celebrations

---

### **Day 1: Requests Basics**
- [ ] Install `requests` (`pip install requests`)
- [ ] Learn GET, POST, PUT, DELETE
- [ ] Pass headers, query params, JSON body
- [ ] Call free APIs & print status + JSON
- [ ] Watch: *Python Requests API Automation with pytest*

✅ **If all checked:** 🎉 *Congrats! You can now make any kind of HTTP request with Python and handle responses confidently!*

---

### **Day 2: Pytest Basics**
- [ ] Install `pytest` (`pip install pytest`)
- [ ] Learn test discovery (`test_*.py`, `test_*` functions)
- [ ] Run with `pytest -v`
- [ ] Use `assert` for validation
- [ ] Watch: *Pytest Tutorial – How to Test Python Code*

✅ **If all checked:** 🎉 *You now know how to set up and run tests with pytest, and validate API responses like a pro!*

---

### **Day 3: Writing API Tests**
- [ ] Create a GET test for `/posts`
- [ ] Create a POST test for `/posts`
- [ ] Validate status code + JSON fields
- [ ] Use variables for URLs to avoid repetition

✅ **If all checked:** 🎉 *Boom! You can now write functional API tests that ensure endpoints work as expected!*

---

### **Day 4: Pytest Fixtures**
- [ ] Learn what fixtures are
- [ ] Create fixture for base URL
- [ ] Use fixture in multiple test functions
- [ ] Explore fixture scope (`function`, `module`)

✅ **If all checked:** 🎉 *Great! You can now write reusable test setups with fixtures, saving time and avoiding repetition!*

---

### **Day 5: Import/Export in Python**
- [ ] Learn `import` and `from ... import`
- [ ] Create `utils.py` with helper functions
- [ ] Import helpers into test files

✅ **If all checked:** 🎉 *Nice! You can now organize your code into reusable modules for cleaner, maintainable projects!*

---

### **Day 6: Logging with structlog**
- [ ] Install `structlog` (`pip install structlog`)
- [ ] Configure basic structured logging
- [ ] Add logs for request & response
- [ ] Check logs in console

✅ **If all checked:** 🎉 *Awesome! You can now log requests and responses in a structured format, making debugging much easier!*

---

### **Day 7: Debugging Basics**
- [ ] Use `print()` and logger for quick checks
- [ ] Use `pdb` to pause execution
- [ ] Run with `pytest -s` to see print/logs
- [ ] Try IDE breakpoints

✅ **If all checked:** 🎉 *Fantastic! You can now debug Python code interactively and track down tricky bugs with ease!*

---

### **Days 8–9: Mini Project**
- [ ] Choose 3–4 endpoints from a public API
- [ ] Write tests using fixtures & logging
- [ ] Add intentional failure for debugging practice
- [ ] Watch: *Build a Robust API Automation Framework with Python*

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
