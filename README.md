## Project Proposal Template:
### Project Title or Name of the Application	:
### Project Title or Name of the Application	: AutoLedger: Finance and Accounting System
### Section			   	      : 9-Lithium
### Group Members			    : GRIÑO, Juan Vincent Miguel, QUIMSON, Marcus Alessandro, YEBRA, Zeph Gabriel
### Date (Proposal Date)  : Nov 13, 2026
### Project Description:

- A brief summary of the project description and the need for it.
- Our accounting system can help record, track, and report financial transactions such as taxes, withdrawals, returns, and investments. It is needed by accountants, managers, business owners, and tax authorities so that financial needs can be tracked and they can comply with financial laws. The target demographic of our application includes both students and adults who need help in tracking financial transactions. Classes include "Transaction", which have the attributes transaction_type (e.g. Investment, Earning) and amount (negative for purchases, positive for earnings), and is used to create transaction objects to be accounted for in the Ledger. The Ledger class logs all transactions and gives the user an easy way to search through their transactions, with attributes history (list of all transactions), and methods record_transaction(transactionObj), print_summary(), get_net_total(), and remove_transaction(index). Lastly, the class "User" provides an object containing the name and role of the user, alongside providing methods to return booleans if the user is able to view or record transactions, called can_record() and can_view_reports(), ensuring that only specific roles (roles included are Accountant, Business Manager, Tax Authority, and Auditor) are able to perform actions (e.g. recording transactions, viewing reports) limited to their role. Methods in the Ledger class take in a User object in its arguments, and bars the user from accessing specific methods if their assigned role is not permitted to perform that method.

- The description is then followed by the class diagram, depicting clearly what was described.

<img width="1188" height="287" alt="image" src="https://github.com/user-attachments/assets/7ae18e08-432b-4617-9d65-4bd0ca82568a" />


### Goals:

- Our project's long term outcome is an application that records, tracks, and reports financial transactions that can be used by anyone, anytime.

- Objective 1: Create and implement an application that can keep track and report financial transactions, making sure the program is well-structured and object-oriented, with properly implemented classes and methods.
- Objective 2: Make it user-friendly, easy to use, and accessible so that anyone can use it at any time and anywhere they are.
- Objective 3: Rigorously test the program to make sure it works properly, then, debug any bugs that are found so it can run smoothly.
