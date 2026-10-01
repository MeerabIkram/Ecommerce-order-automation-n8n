# E-Commerce Order Automation System

An automated order processing system built with **n8n** and **Google Sheets**.
Completed as part of the **Big Brains Learning** internship.

## Overview
This project automates the full journey of an online store order: from creating the order to recording its fulfillment. It reduces manual work and handles wrong cases (like failed payments or low stock) safely.

## Problem
Handling orders by hand is slow and causes mistakes, such as missed payments, stock errors and late confirmations.

## Objectives
- Automate order, payment, stock, confirmation and fulfillment steps
- Keep inventory accurate automatically
- Handle errors and invalid data safely

## How It Works
1. **Order Created:** a new order is received and validated
2. **Payment Verified:** the payment is checked (paid / failed / mismatch)
3. **Inventory Updated:** stock is checked and reduced automatically
4. **Order Confirmed:** a confirmation message is sent
5. **Fulfillment Recorded:** the order is saved in the fulfillment records

## Tools & Technologies
- n8n (workflow automation)
- Google Sheets (database)
- Gmail / notification node (confirmations)
- Set, IF and Code nodes (logic and validation)

## Key Features
- Order creation with validation
- Payment check with failed and mismatch handling
- Stock check and automatic inventory update
- Order confirmation message
- Google Sheets integration


## How to Use
1. Import the workflow JSON file into n8n.
2. Connect your own Google Sheets and email credentials in n8n.
3. Use the sample/test data to run a test order.
4. Check the execution and the updated sheets.

> **Note:** Only test data is used in this project. No passwords, API keys or private credentials are included in this repository.

## Challenges & Learning
- Connecting Google Sheets and matching data fields
- Handling failed payments and low stock
- Learned triggers, nodes, expressions, IF logic, debugging and error handling

## Future Improvements
- Real payment gateway integration
- WhatsApp / SMS alerts for customers
- Dashboard for sales and stock

## Author
**Meerab Ikram**


Big Brains Learning Internship



Thanks to **Big Brains Learning** for the opportunity.
