# Expense Tracker
The Expense Tracker is a simple, responsive web app that allows users to manage their personal finances by adding incomes and expenses. It calculates and displays the balance, total income, and total expenses in real-time.

🚀 Features
✅ Add transactions

Add incomes (positive values) and expenses (negative values).

✅ Real-time balance update

The app displays your current balance, total income, and total expenses dynamically.

✅ Transaction history

View a list of all transactions with easy distinction between income and expenses.

✅ Delete transactions (if implemented in script.js)

Optionally, remove unwanted transactions.

✅ Input validation

Notifies you if required fields are left empty.

✅ Responsive design

Works smoothly on desktop and mobile browsers.

📂 Project Structure
bash
Copy
Edit
expense-tracker/
├── index.html        # Main HTML file
├── style.css         # CSS styles
├── script.js         # JavaScript logic
└── README.md         # Project documentation


⚙️ Getting Started
1️⃣ Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/expense-tracker.git
2️⃣ Navigate to the project directory
bash
Copy
Edit
cd expense-tracker
3️⃣ Open the app
You can simply open index.html in your web browser:

bash
Copy
Edit


bash
Copy
Edit
Example using Python
python3 -m http.server
Then visit http://localhost:8000.

🛠 Usage
1️⃣ Open the app in your browser.
2️⃣ Select an expense Category (e.g., Food & Beverage, Rent).
3️⃣ Enter the Amount (numbers only).
4️⃣ Choose the Date of the expense.
5️⃣ Click Add to save the entry.
6️⃣ The expense will appear in the list with the category, amount, and date.
7️⃣ Click Delete to remove any expense from the list.
8️⃣ The Total amount updates automatically as you add or remove expenses.

📌 Example Categories
The app supports a wide range of expense categories:

Food & Beverage

Rent

Transport

Relaxing

Utilities

Entertainment

Healthcare

Education

Shopping

(You can easily extend this list by modifying the HTML select element.)

📝 Future Enhancements
🔹 Data Persistence

Add LocalStorage / IndexedDB to save expenses between sessions.

🔹 Expense Filtering

Filter by date range or category.

🔹 Charts and Analytics

Visualize expenses using pie charts or bar graphs.

🔹 Export Options

Export your expenses as CSV or PDF.

🔹 Mobile App

Build a mobile version using React Native or Flutter.

🎨 Screenshots
![image](https://github.com/user-attachments/assets/e979d59e-acb5-4f8a-961f-3e7aba6e866d)


💻 Technologies Used
HTML5

CSS3

Vanilla JavaScript (ES6)
