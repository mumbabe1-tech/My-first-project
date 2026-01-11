Python Banking System — Operational Data Simulation (Jupyter Notebook in VS Code)

This project implements a simple **Python-based banking system** designed to simulate how financial institutions capture, validate, and manage operational data. The entire application was developed and executed inside a **Jupyter Notebook (.ipynb)** using **VS Code’s Jupyter extension**, making it beginner-friendly while still demonstrating structured data handling and core programming logic.

Project Overview  
This simulated banking environment supports essential account operations:
- Create new customer accounts  
- Deposit funds  
- Withdraw funds  
- Check account balances  
- View transaction history  

All data is stored **in memory** using Python dictionaries and lists. This mirrors how raw operational data is generated before being stored in databases or used for analytics in real financial systems.

 Data‑Engineering‑Aligned Structure  
Although this project does not use SQL or external storage, it still demonstrates foundational data-engineering concepts:

Structured Data Representation
The system uses:  
- **Dictionaries** to store customer and account information  
- **Lists** to maintain transaction logs  

This reflects how operational data is structured before entering a database or pipeline.

Data Capture & Event Logging  
Each user action generates a structured event containing:  
- Timestamp  
- Transaction type  
- Amount  
- Updated balance  

This simulates the raw data layer of a financial system.

Data Validation & Business Rules 
The application enforces essential rules such as:  
- Preventing overdrafts  
- Ensuring valid account numbers  
- Maintaining accurate balances  
- Logging every transaction consistently  

These are core principles in financial data quality and governance.

Traceability & Auditability
The transaction history acts as an audit trail, similar to what financial institutions use for compliance and internal reporting.

How to Run the Project (Jupyter Notebook in VS Code)
This project runs entirely inside a Jupyter Notebook using the VS Code Jupyter extension.
1. Install VS Code Extensions
Ensure the following extensions are installed:
- **Python**
- **Jupyter**

2. Open the Notebook
Open the `.ipynb` file directly in VS Code.

3. Select a Python Kernel
VS Code will prompt you to choose a Python interpreter.  
Any Python 3.x environment works.

4. Run the Notebook Cells
Execute each cell in order:

- Early cells define the data structures and functions  
- Later cells run the menu-driven banking system  
- Follow the prompts to create accounts, deposit, withdraw, and view transaction history  

5. No Additional Setup Required
All data is stored **in memory** during runtime.  
No database, external files, or command-line execution is needed.

Tech Stack  
- Python  
- Jupyter Notebook (.ipynb)  
- VS Code with Jupyter extension  
- Dictionaries & lists for in-memory storage  
- Functions, loops, and conditional logic  
 Purpose  
This project demonstrates how operational data is:  
- Captured  
- Structured  
- Validated  
- Logged  
