# 📘 Booktime API Automation Tests

This repository contains automated API test collections for the Booktime platform using Postman.

---

## 📁 Project Structure

- Auth OTP + TCs.postman_collection.json
- Books + TCs.postman_collection.json
- Language+ TCs.postman_collection.json
- Levels + TCs.postman_collection.json
- Series + TCs.postman_collection.json
- Streaks + TCs.postman_collection.json
- Users+ TCs.postman_collection.json
- dev.postman_environment.json

---

## 📊 HTML Reports

- auth-report.html
- books-report.html
- language-report.html
- levels-report.html
- series-report.html
- streaks-report.html
- users-report.html

---

## 🚀 How to Run

### Using Postman
1. Import all collections
2. Import environment file
3. Run collections

---
## Tools Used

### 1. Postman
Used for creating and managing API test collections.

### 2. Newman
Command-line tool used to run Postman collections.

Install Newman:
```bash
npm install -g newman

### 3. Newman HTML Reporter from
npm install -g newman-reporter-htmlextra

### 4. Required to run Newman and npm packages
Download Node.js
by: node -v
npm -v
---
### ▶ Run Single Collection

```bash
newman run "Auth OTP + TCs.postman_collection.json" -e dev.postman_environment.json
newman run "Books + TCs.postman_collection.json" -e dev.postman_environment.json
newman run "Series  + TCs.postman_collection.json" -e dev.postman_environment.json
newman run "Language+ TCs.postman_collection.json" -e dev.postman_environment.json
newman run "Levels +TCs.postman_collection.json" -e dev.postman_environment.json
newman run "Users+ TCs.postman_collection.json" -e dev.postman_environment.json

### ▶ OPen ALL Collection
open *.html
