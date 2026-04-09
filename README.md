# Employee Payroll System in C

A **console-based Employee Payroll Management System** written in C with CSV storage and user authentication. The system supports **login, signup, employee management, and Excel-ready CSV export**, with **admin and user roles**.

---

## Features

- **User Authentication**
  - Login for existing users.
  - Signup for new users with role assignment (`admin` or `user`).
  - Passwords are stored as hashed values for basic security.

- **Admin Capabilities**
  - Add new employees.
  - Update existing employee details.
  - Delete employees.
  - View all employee records.

- **User Capabilities**
  - View employee records.
  - Search employees by ID.

- **Employee Records**
  - Stored in `employee.csv` in **Excel-ready format**.
  - Fields: ID, Name, Basic Salary, HRA, DA, Deductions, Net Salary.
  - Prevents duplicate employee IDs.

- **Console UI**
  - Pretty table output for employee list.
  - Menu-driven system.

---

## Requirements

- C compiler (tested on `gcc`).
- Windows / Linux / macOS terminal.

---

## Usage

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/employee-payroll-system.git
cd employee-payroll-system
