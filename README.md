Expense.fyi – Smart Expense Tracker

Expense.fyi is a modern, responsive, and intuitive web application to manage personal finances. Track your expenses, income, investments, and subscriptions effortlessly. Built with Next.js, Supabase, and Prisma, it offers a seamless experience across devices.

Table of Contents

Demo

Features

Tech Stack

Installation

Environment Variables

Usage

Contributing

License

Demo

Live demo: https://your-domain.com

Screenshots & Demo Videos: Check the public/demo folder.

Features

Expense Management: Track daily expenses and categorize them.

Income & Investments: Monitor income sources and investments.

Subscriptions: Manage recurring payments and plans.

Reports & Analytics: Visual charts for insights.

User Authentication: Secure signup and login using Supabase.

Export Data: Export financial data for analysis.

Responsive Design: Fully mobile-friendly interface.

Tech Stack

Frontend: Next.js 14, TypeScript, Tailwind CSS

Backend / Database: Supabase, Prisma ORM, PostgreSQL

Authentication: Supabase Auth

Notifications / Email: Resend API

Other Tools: Husky (Git hooks), PostCSS, Browserlist

Installation

Clone the repository

git clone https://github.com/NageswaraRao47/smart-expense-tracker.git
cd smart-expense-tracker/expense.fyi-main


Install dependencies

npm install


Create a .env.local file in the root directory:

SUPABASE_DB_URL=<your-supabase-db-url>
NEXT_PUBLIC_SUPABASE_URL=<your-supabase-url>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<your-supabase-anon-key>
PRISMA_FIELD_ENCRYPTION_KEY=<your-encryption-key>
RESEND_API_KEY=<your-resend-api-key>
NEXT_PUBLIC_SITE_URL=http://localhost:3000


Run the development server

npm run dev


Open http://localhost:3000
 in your browser.

Usage

Sign Up / Login: Create an account or log in using your email.

Dashboard: View summaries of your expenses, income, and subscriptions.

Add Transactions: Add new expenses, income, or investments.

Export: Export your financial data as CSV or PDF.

Contributing

Fork the repository

Create a feature branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m 'Add feature')

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

License

This project is licensed under the MIT License
.
