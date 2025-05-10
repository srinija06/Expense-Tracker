# Expense Tracker

A simple and intuitive web application to track your personal expenses and budget.

## Features

- Track both expenses and income
- View current balance
- Categorize transactions
- Search through transaction history
- Responsive design for mobile and desktop

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/ExpenseTracker.git
cd ExpenseTracker
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3001`

## Project Structure

```
ExpenseTracker/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── AddTransaction.js
│   │   ├── OverviewComponent.js
│   │   ├── Tracker.js
│   │   ├── TransactionItem.js
│   │   └── TransactionsContainer.js
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── globalStyles.js
│   └── reportWebVitals.js
├── package.json
├── package-lock.json
└── README.md
```

## Usage

1. Add a new transaction by entering the amount and details
2. Select whether it's an expense or income
3. Click "Add Transaction" to save it
4. View your transactions list below
5. Use the search box to filter transactions
6. The balance, total expense, and total budget are displayed at the top

## Technologies Used

- React.js
- CSS/Styled Components
- LocalStorage for data persistence

## Future Enhancements

- Data visualization with charts
- Export transactions to CSV
- Categories and tags for better organization
- Monthly/yearly expense reports
- Dark mode

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

