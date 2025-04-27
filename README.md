# 🧾 Daily Finance Tracker

The **Daily Finance Tracker** is a simple, lightweight web application to help you manage your daily expenses and income. It lets you add, view, and analyze your transactions — and it keeps your data safe even after page reloads using the browser's **LocalStorage**.

## ✨ Features

- **Add Expenses and Income:** Enter amount, category, date, and description easily.
- **Persistent Storage:** Data is stored in the browser's **localStorage** — even after refreshing or closing the tab.
- **Transaction History:** View all your past entries in a clean list format.
- **Real-Time Balance Update:** Instantly see your daily balance based on your transactions.
- **Responsive Design:** Optimized for mobile and desktop screens.

## 📦 Technologies Used

- **HTML5** - Structure of the application.
- **CSS3 / Tailwind CSS** - Styling for modern UI.
- **JavaScript (Vanilla)** - Core functionality and data handling.
- **Chart.js** _(Optional if you added charts)_ - For visual breakdowns of expenses/income.
- **FontAwesome** _(Optional)_ - For adding icons.

## 🚀 Getting Started

1. **Clone or Download the Repository**:

   ```bash
   git clone https://github.com/your-username/daily-finance-tracker.git
   cd daily-finance-tracker
   ```

2. **Open the Application**:

   Simply open `index.html` in your web browser.

---

## 🔥 How to Use

1. **Add a Transaction**:

   - Click on the "Add Expense" or "Add Income" buttons.
   - Enter the transaction details (amount, category, date, description).
   - Click "Add" to save the transaction.

2. **View Transactions**:

   - All your added transactions will appear in a list.
   - Each transaction shows its type (expense/income), amount, category, and date.

3. **Update your Balance**:

   - The application automatically calculates your balance based on your transactions.

4. **Persistent Storage**:

   - Transactions are automatically saved into your browser’s localStorage.

5. **Clear Data (Optional)**:
   - You can manually clear localStorage from browser settings if you want to reset the app.

---

## 📂 Project Structure

```plaintext
finance-tracker/
├── index.html          # Main HTML file
├── style.css           # CSS Styling (Tailwind or custom)
├── app.js              # JavaScript functionality
├── README.md           # Project documentation
```

---

## 🛠 LocalStorage Explained

- **Saving:**

  ```javascript
  localStorage.setItem("transactions", JSON.stringify(transactions));
  ```

- **Loading:**

  ```javascript
  const transactions = JSON.parse(localStorage.getItem("transactions")) || [];
  ```

- Your data stays available **even after refreshing** or **closing** the browser.

---

## 🧩 Future Improvements

- Export transactions to a CSV file.
- Add category-wise pie charts.
- Monthly expense/income summaries.
- Add authentication for multiple users (with database support).
- Dark mode 🌙.

---

## 👨‍💻 Author

Made with ❤️ by [Ali Gohar](https://github.com/AliGohar2151).
