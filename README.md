<div align="center">

# Hi, I'm Owais Shaikh 👋

### Full-Stack Developer building web apps, mobile apps, and dev tooling

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/owais-shaikh-8bb55333a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:owaisshaikh376@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OwaisShaikh1)

</div>

---

## About Me

- 💻 Full-stack developer and student, building projects across web, mobile, and ML
- 🛡️ Core team member on **CyberSentinel**, a group ML project for network intrusion detection
- ✍️ Built **Writer**, an offline-first Flutter writing app with a Node/MySQL backend
- 📱 Built **SmsDBIT**, a bulk SMS delivery portal for an organization
- ✅ Built **FinanceFlow**, a finance/tax management platform (Next.js, TypeScript, Node.js)
- 🎓 Built **SmartScore**, a student evaluation & exam-tracking platform
- 🎲 Explore algorithms for fun — backtracking for Sudoku, minimax with alpha-beta pruning and bitboards for Chess
- 📍 Based in Mumbai, India

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Databases & Tools**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Featured Projects

### 🛡️ [CyberSentinel](https://github.com/Zaheen-Siddiqui/CyberSentinel) *(group project)*
A multi-model network intrusion detection system trained on the NSL-KDD dataset, built as part of the core team. A two-stage pipeline first classifies traffic as normal or attack, then breaks down the attack category (DoS, Probe, R2L, U2R) using RandomForest, SVM, and XGBoost, with a Flask/React dashboard for live model comparison.
**Results:** All three models trained to over 99% accuracy on the training data (RandomForest and XGBoost: 99.91%, SVM: 99.16%). On unseen test traffic, which includes attack types the models weren't trained on, XGBoost generalized best with **78.99% accuracy** — the most realistic measure of real-world performance.
**Stack:** `Python` `scikit-learn` `XGBoost` `Flask` `React`

### ✍️ Writer — [Frontend](https://github.com/OwaisShaikh1/Flutter-writer) & [Backend](https://github.com/OwaisShaikh1/FlutterWriterBackend)
An offline-first literature/writing platform. The Flutter client lets users read and author chapters, writing to a local Drift (SQLite) database first and queuing changes for background sync once connectivity returns — so reading and drafting keep working offline. State is managed through dedicated providers (`AuthProvider`, `LiteratureProvider`, `SyncProvider`), and content is drafted in markdown.

The Node.js/Express + MySQL backend exposes REST routes for authentication, literature items, and chapters (`/register`, `/login`, `/items`, `/chapters`, etc.), with JWT-based auth, bcrypt password hashing, and ownership checks so only an author can edit or delete their own work. It also serves cover/content images from static paths.
**Stack:** `Flutter` `Dart` `Node.js` `Express` `MySQL` `JWT`

### 📱 [SmsDBIT](https://github.com/OwaisShaikh1/SmsDBIT)
A bulk SMS delivery portal for an organization, with teacher login, sender-ID management, group management, and a template-approval workflow.
**Stack:** `HTML/CSS` `JavaScript`

### 💰 [FinanceFlow](https://github.com/OwaisShaikh1/FinanceFlow)
A finance and tax-management web platform ("CA Assistant"), built to help individuals and small businesses track income, expenses, invoices, and tax deadlines from a single dashboard.
**Stack:** `Next.js` `TypeScript` `Node.js` `MongoDB`

### 🎓 [SmartScore](https://github.com/OwaisShaikh1/pi5mini)
A web application for student evaluation and scoring — enabling quizzes and exams, and tracking student performance across multiple subjects and departments, with role-based authentication and authorization.
**Stack:** `Python` `JavaScript` `CSS`

### 🎲 Games & Algorithms — [Sudoku](https://github.com/OwaisShaikh1/Sudoku) · [Checkers (Rust)](https://github.com/OwaisShaikh1/checkers_rust) · [Chess Bots](https://github.com/OwaisShaikh1/chessbots)
Side projects exploring classic board-game logic and computationally interesting problems, built out of curiosity about search and game-tree algorithms:
- **Sudoku** — solver built using **backtracking**
- **Checkers** — engine in Rust
- **Chess Bots** — bots in Python/C++ using **minimax with alpha-beta pruning** and **bitboard** board representations, evaluated against engines like Stockfish
**Stack:** `TypeScript` `Rust` `Python` `C++`

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=OwaisShaikh1&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OwaisShaikh1&layout=compact&theme=radical&hide_border=true&langs_count=8" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=OwaisShaikh1&theme=radical&hide_border=true)

</div>

---

## Let's Connect

<p align="left">
<a href="https://www.linkedin.com/in/owais-shaikh-8bb55333a/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:owaisshaikh376@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<div align="center">
<sub>⭐ Open to collaborations and interesting projects — feel free to reach out.</sub>
</div>
