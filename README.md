# 🧪 Banking Web App Playground

<section align="center">
   <p>Banking Web App Playground is a basic banking system simulator developed to practice and learn web development with Vue 3. The application supports core functionalities such as login, deposit-withdrawal, and transaction history management, emphasizing efficient state management and client-side data persistence.</p>
    <img alt="Vue 3 Badge" src="https://img.shields.io/badge/Vue%203-transparent?style=for-the-badge&color=%234FC08D">
    <img alt="Vite Badge" src="https://img.shields.io/badge/Vite-transparent?style=for-the-badge&color=%23646CFF">
    <img alt="Pinia Badge" src="https://img.shields.io/badge/Pinia-transparent?style=for-the-badge&color=%23FFD859">
    <img alt="Vue Router Badge" src="https://img.shields.io/badge/Vue%20Router-transparent?style=for-the-badge&color=%234FC08D">
    <img alt="Bootstrap 5 Badge" src="https://img.shields.io/badge/Bootstrap%205-transparent?style=for-the-badge&color=%237952B3">
    <img alt="JavaScript Badge" src="https://img.shields.io/badge/JavaScript-transparent?style=for-the-badge&color=%23F7DF1E">
    <img alt="ESLint Badge" src="https://img.shields.io/badge/ESLint-transparent?style=for-the-badge&color=%234B32C3">
    <img alt="Prettier Badge" src="https://img.shields.io/badge/Prettier-transparent?style=for-the-badge&color=%23F7B93E">
</section>

## 📖 Table of Contents

- ✨ [Key Features](#key-features)
- 🚀 [Getting Started](#getting-started)
- 📝 [Learning Log / Notes](#learning-log--notes)

## ✨ Key Features

- **Authentication:** Simulated login system with data validation (e.g., email format and password length checks).
- **Banking Operations:** Supports deposit and withdrawal transactions with balance validation and error notifications.
- **Transaction History:** Displays a complete list of transactions, including date, user email, transaction type, and amount.
- **Transaction Management:** Allows editing and deleting of past transactions.
- **Data Persistence:** Saves transaction data and login status to the browser's `LocalStorage`, ensuring data remains available after refreshing or closing the page.

## 🚀 Getting Started

### Prerequisites

- Node.js (Version 20.19.0 or higher)
- npm (Comes installed with Node.js)

### Installation & Running

1. Clone this project to your local machine.
2. Navigate to the `client` folder:
   ```bash
   cd client
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the project in development mode:
   ```bash
   npm run dev
   ```
5. Open your browser and go to the displayed URL (usually `http://localhost:5173`).

## 📝 Learning Log / Notes

- **State Management with Pinia:** Separating stores into `user` (for login management) and `bank` (for transaction management) keeps the code organized. Using Getters allows for real-time balance calculation.
- **Vue Router Navigation Guards:** Using `beforeEach` to check the `isLoggedIn` status from LocalStorage prevents unauthorized access to Deposit or Transaction pages.
- **LocalStorage Integration:** Learned how to sync data from Pinia State to LocalStorage for data persistence, reloading it when the application starts.
- **Bootstrap 5 & Modals:** Utilizing Bootstrap for layout and controlling Modals via JavaScript to display edit forms or deletion confirmations.
- **Vue Composition API:** Writing code with `<script setup>` makes it more concise and readable, including the use of `ref` and `computed` for reactive data management.

---

🤝 Open to any suggestions or feedback and feel free to contribute to this project.
