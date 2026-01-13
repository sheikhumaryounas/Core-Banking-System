NexBank – Core Banking System Simulation

NexBank is a web-based Core Banking System (CBS) simulation developed to demonstrate the critical importance of data integrity, transactional safety, and consistency in modern financial applications. The project focuses on implementing SQL Transaction Control Language (TCL) commands—COMMIT, ROLLBACK, and SAVEPOINT—to ensure reliable and secure banking operations.

Built using Next.js for the frontend and backend logic, along with PostgreSQL as the relational database, NexBank simulates real-world banking workflows such as customer management, account handling, and fund transfers.

🚀 Features

👤 Customer Management
Create and manage customer profiles
Store customer-related information securely

🏦 Account Management
Create bank accounts linked to customers
Maintain accurate account balances

💸 Fund Transfer System
Transfer funds between accounts
Prevent partial or inconsistent transactions

🔐 Transaction Integrity
Uses SQL COMMIT to permanently save successful operations
Uses ROLLBACK to revert changes on failure
Uses SAVEPOINT for partial rollbacks within a transaction

📊 Real-Time Simulation
Demonstrates how real banking systems maintain consistency under failure conditions

🛠️ Tech Stack
Technology	Purpose
Next.js	Full-stack web framework
PostgreSQL	Relational database
SQL (TCL)	Transaction control & integrity
Node.js	Backend runtime
HTML / CSS / JavaScript	UI and logic
🧠 Core Concept: Transaction Control Language (TCL)

This project is primarily focused on demonstrating ACID properties of databases:

Atomicity – Transactions are fully completed or fully rolled back

Consistency – Database remains in a valid state

Isolation – Concurrent transactions do not interfere

Durability – Committed data is permanently saved

Example Use Cases:

If a fund transfer fails midway, ROLLBACK ensures no money is lost.

SAVEPOINT allows partial recovery without canceling the entire transaction.

COMMIT confirms all operations are successfully completed.

📂 Project Structure (Simplified)
NexBank/
│
├── pages/            # Next.js pages
├── components/       # Reusable UI components
├── lib/              # Database & utility functions
├── sql/              # SQL queries and transaction logic
├── public/           # Static assets
├── styles/           # CSS styles
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
https://github.com/sheikhumaryounas/Core-Banking-System
cd nexbank 
2️⃣ Install Dependencies
npm install
3️⃣ Configure Environment Variables
Create a .env file and add:
DATABASE_URL=postgresql://username:password@localhost:5432/nexbank
4️⃣ Run the Development Server
npm run dev

The application will be available at:
http://localhost:3000

🧪 Educational Use Case
This project is ideal for:
Database Management System (DBMS) courses
Learning transaction handling in SQL
Understanding real-world banking system logic
Academic demonstrations and mini-projects
🔮 Future Enhancements
🔑 User authentication & role-based access
📈 Transaction history and reporting
🧾 Audit logs for compliance
🌐 Deployment on cloud platforms
🔒 Enhanced security features
📜 License
This project is developed for educational purposes.
You are free to use, modify, and extend it with proper attribution.

🙌 Author
Umar
Computer Science Student / Developer
