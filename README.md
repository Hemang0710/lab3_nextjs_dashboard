# Lab 4
# Name:- Hemang Patel  Id:-N01652658
# Next.js Dashboard App

This project is a **Next.js Dashboard Application** built by following the [Next.js Dashboard tutorial](https://nextjs.org/learn/dashboard-app/setting-up-your-database) (Chapters 6 to 11). It uses **Next.js 15**, **TypeScript**, **Turbopack**, **PostgreSQL**, and **Tailwind CSS** for styling.

## 🗂️ Chapters Summary

### 📌 Chapter 6: Setting Up Your Database
- Learn how to connect your app to a PostgreSQL database using SQL.js and environment variables.

### 📌 Chapter 7: Fetching Data from the Database
- Implement data fetching functions to query invoices, customers, and revenue data.

### 📌 Chapter 8: Displaying Data in the UI
- Create and display cards and charts with fetched data on the dashboard.

### 📌 Chapter 9: Handling Errors
- Add error handling to manage failed data fetches gracefully.

### 📌 Chapter 10: Working with Loading UI
- Add loading states to the UI for better user experience during data fetching.

### 📌 Chapter 11: Final Touches
- Polish the UI with improved styling, proper layout, and finishing details.

---

## ⚠️ Challenges Faced

- **Database Connection Issues:** Errors like `ENOTFOUND your-postgres-url-here` if the `.env.local` is not properly set up.
- **Environment Variables:** Forgetting to restart the dev server after updating `.env.local` may lead to persistent connection errors.
- **Async Data Fetching:** Managing loading and error states across different components.
- **SQL Queries:** Understanding how SQL.js queries are written inside Next.js functions.
- **Typescript Types:** Ensuring type safety in API responses and component props.

---

## 🛠️ Technologies Used

- **Next.js 15 (App Router)**
- **TypeScript**
- **PostgreSQL (via SQL.js)**
- **Tailwind CSS**
- **Turbopack**

---

## 🗄️ Database Setup

1. Create a PostgreSQL database using a service like Supabase, Neon, Railway, or local setup.
2. Get your database connection string (e.g., `postgresql://username:password@host:port/database`).
3. Create a `.env.local` file in your project root and add:

   ```bash
   DATABASE_URL=your-postgres-connection-string
