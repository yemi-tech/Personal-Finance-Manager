# Personal Finance Manager (Java)

A Java-based desktop/console application to help you manage your income, expenses, and budgets using clean object-oriented design. No web UI, no bloat—just clear reports and financial awareness.

---

## 📋 Features

- Create and manage multiple users
- Add, edit, and delete transactions
- Categorize income and expenses
- Set monthly budgets per category
- View budget reports and warnings
- Save and load data to/from disk (JSON or SQLite)

---

## 🧱 Tech Stack

- **Language**: Java 17+
- **Build Tool**: Maven
- **Testing**: JUnit 5
<!-- - **Persistence**: JSON via Gson or database via SQLite + JDBC
- **Optional GUI**: JavaFX (planned for future) -->

---

## 🎯 OOP Design Overview

Key classes include:

- `User`: Represents a user's profile, including transactions and budgets
- `Transaction`: Represents an income or expense record
- `Category`: Represents a user-defined category (e.g. Food, Rent)
- `Budget`: Represents monthly spending limits
- `FinanceManager`: Main service handling business logic
- `ReportGenerator`: Outputs spending summaries
- `FileManager`: Handles saving/loading data

> Designed using SOLID principles with a focus on clean code and separation of concerns.

---

## 🖥️ How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yemi-tech/personal-finance-manager.git
   cd personal-finance-manager
