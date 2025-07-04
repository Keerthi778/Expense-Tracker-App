 Expense Tracker
JavaScript CSS HTML

A simple yet powerful expense tracking application that helps you manage your finances with local storage persistence.

✨ Features
📊 Track income and expenses
💾 Local storage persistence
📱 Responsive design
📈 Real-time balance calculation
🔔 Form validation notifications
🗑️ Delete transaction functionality
💵 Indian Rupee (₹) formatting
🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)
Storage: Browser LocalStorage
Styling: Custom CSS with modern shadows and transitions
Icons: Simple budget icon
🚀 Quick Start
Clone the repository:

git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker
Open index.html in your browser:

open index.html  # On macOS
start index.html # On Windows
📋 Usage Guide
Adding Transactions
Enter a description (e.g., "Groceries")
Enter amount:
Positive for income (e.g., 5000)
Negative for expenses (e.g., -200)
Click "Add transaction"
Managing Transactions
✏️ Transactions appear in history list
❌ Hover over transaction and click "×" to delete
💰 Balance updates automatically
📂 File Structure
expense-tracker/
├── index.html          # Main application file
├── style.css           # All styling rules
├── script.js           # Core functionality
└── README.md           # Documentation
🎨 UI Components
Component	Description	Classes
Balance Card	Shows total balance	.balance-container
Income/Expense	Summary cards	.inc-exp-container
History List	Transaction records	.list
Form	Add new transactions	#form
Notification	Error messages	.notification-container
🔧 Customization
Change Colors
Modify in style.css:

:root {
  --income-color: #2ecc71;      /* Green */
  --expense-color: #c0392b;     /* Red */
  --primary-color: #9c88ff;     /* Purple */
  --shadow: 0 1px 3px rgba(0,0,0,0.12);
}
Change Currency
Update in script.js:

function formatRupees(num) {
  return '₹' + num.toLocaleString('en-IN');
  // Change to '$' + num.toFixed(2) for USD
}

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
