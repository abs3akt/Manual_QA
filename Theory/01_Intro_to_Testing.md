
# 🧪 Introduction to Software Testing

Software testing is the process of evaluating and verifying that a software product or application does what it is supposed to do.

---

## 🎯 Goals of Testing

- Prevent defects from reaching production
- Find and report bugs early
- Ensure the product meets requirements
- Improve product quality
- Validate user expectations

---

## 🔍 Types of Testing

### Functional Testing
- Manual testing
- Automation testing
- Acceptance testing

### Non-Functional Testing
- Performance testing
- Security testing
- Usability testing

---

## 📦 Testing Levels

1. **Unit Testing**
2. **Integration Testing**
3. **System Testing**
4. **Acceptance Testing (UAT)**

---

## 🧠 Key Terms

- **Test case** – a set of actions to verify a feature
- **Bug/Defect** – an issue where actual behavior differs from expected behavior
- **Requirement** – documented expectations for the system
- **User Story** – description of functionality from user perspective

---

## ✔ Summary

Testing is not about “breaking” software, but about ensuring that it works correctly, meets user needs, and maintains high quality.

---

🧠 Golden Rule (Junior QA Git Flow)

Memorize this workflow:

git pull
git add .
git commit -m "message"
git push


If you see "rejected" → use:

git pull --rebase origin main
git push

✔️ What if you edited something directly on GitHub?

You now have online commits + local commits → a rebase is required:

git pull --rebase origin main
git push

⚠️ Important

Do NOT use:

git push --force


as a beginner.
It can overwrite other people’s work or delete commits from the repository.
