# Financial Management App with React.js

This project is a simple financial management application built using React.js. The main purpose of this app is to help users track their income and expenses by storing transaction data in the browser's local storage.

### Features

- **Add Transactions:** Users can add new transactions by providing a description, amount, and selecting whether it's an income or expense.
- **Track Balance:** The app calculates and displays the total income, total expenses, and the overall balance based on the entered transactions.
- **Local Storage:** Transaction data is stored in the browser's local storage, allowing users to access their financial data even after refreshing the page or reopening the app.

### Technologies Used

- **React.js:** The frontend of the application is built using React.js, a popular JavaScript library for building user interfaces.
- **Styled Components:** Styling is done using styled components, a CSS-in-JS library that allows for scoped styling and component-based design.
- **Local Storage:** Browser's local storage is utilized to store transaction data, ensuring persistence of data between sessions.

### How to Run

1. Clone the repository to your local machine: `git clone https://github.com/Isaac-Lima/Financial-App.git`
2. Navigate to the project directory: `cd financial-app`
3. Install libraries: `yarn add styled-components react-icons`
4. Start the development server: `npm start`
5. Open your browser and go to `http://localhost:3000` to view the app.

### Usage

1. Add a new transaction by entering a description, amount, and selecting the type (income or expense).
2. The app will automatically update the balance, total income, and total expenses based on the entered transactions.
3. Transactions are saved in the browser's local storage, so you can close the app and reopen it without losing your data.
