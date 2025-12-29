# 💱 Currency Converter

A simple **React + Vite** project that allows users to convert currencies in real-time using an open-source API.  
This project demonstrates the use of React hooks (`useState`, `useEffect`), a custom hook for fetching currency data, and a swap function to toggle between "from" and "to" currencies.

---

## 🚀 Features
- Convert between multiple currencies using live exchange rates.
- Built with **React** and **Vite** for fast development and hot-reloading.
- **Custom Hook** (`useCurrencyInfo`) created to fetch and manage currency data.
- **Swap Functionality**: Instantly swap "from" and "to" currencies.
- Responsive UI styled with **Tailwind CSS**.
- Uses an **open-source API** for currency exchange rates:
  ```js
  fetch(
    `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/${currency}.json`
  )
