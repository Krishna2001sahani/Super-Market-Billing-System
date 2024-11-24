# Supermarket Billing System

A Python-based interactive billing system for supermarkets, allowing customers to add multiple items to their cart, calculate totals, apply discounts, and generate an itemized receipt.

## Features

- **Interactive User Input**: Allows customers to input product names and quantities.
- **Predefined Product Catalog**: Contains a dictionary of common supermarket items with their prices.
- **Cart Management**: Dynamically updates the cart with item details, including price and quantity.
- **Discount Application**: Applies tiered discounts based on the total bill amount:
  - 5% for bills up to ₹500
  - 7% for bills between ₹501 and ₹1000
  - 15% for bills between ₹1001 and ₹5000
  - 20% for bills above ₹5000
- **Itemized Receipt**: Displays product names, rates, quantities, subtotals, total bill, discounts applied, and the final amount.
- **Multi-Customer Support**: Processes transactions for multiple customers in one session.

## Getting Started

### Prerequisites
- Python 3.x installed on your system.

### Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/supermarket-billing-system.git
  
