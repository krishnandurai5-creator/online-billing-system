# Online Billing System

Student: Ajay Karthikeyan K | Register No: 2503917720521007 | Course: B.Tech | Subject: Software Engineering

A command-line billing application built with Python 3 and SQLite. It manages products and customers, builds a cart, calculates discount and GST, generates invoices, records payments and tracks invoice status.

## Problem statement and objectives
Shops that bill on paper or in spreadsheets make calculation mistakes and cannot track unpaid invoices. This system automates the product catalogue, customer records, bill calculation, invoicing and payment tracking.

## Features / modules
| Module | Features |
|---|---|
| products | add, list, search, remove |
| customers | register, list |
| cart | add, remove, view bill |
| invoices | generate, history, record payment, cancel |

Business rules: 5% discount when subtotal >= Rs. 1000; GST 18% on the discounted amount; 1-100 of a product per invoice; invoice flow Unpaid -> Paid; only Unpaid invoices can be cancelled.

## Technology stack
Python 3 (standard library only: sqlite3, unittest, datetime, re), SQLite 3, Git and GitHub.

## Prerequisites and installation
Python 3.9+ and Git. No extra packages.
    git clone <repository-url>
    cd online-billing-system

## Run
    python main.py

## Tests
    python -m unittest -v     (27 of 27 passed)

## Known limitations
CLI only, no login, no real payment gateway, single shop, local SQLite database.

## Future enhancements
Web front end, user roles, PDF invoice export, UPI/card gateway, email/SMS invoices.

## Team member details and individual contributions
Ajay Karthikeyan K (2503917720521007) - individual project: design, coding, testing and documentation.
