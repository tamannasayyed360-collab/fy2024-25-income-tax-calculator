# Income Tax Calculator (FY 2024-25)

A responsive web-based Income Tax Calculator for Indian salaried individuals for Financial Year 2024-25.

The application supports both New and Old tax regimes and provides a detailed tax breakdown along with automated regime comparison.

Live Application:  
https://tamannasayyed360-collab.github.io/fy2024-25-income-tax-calculator/

---

## Overview

This Income Tax Calculator implements Indian income tax slab logic for FY 2024-25. It allows users to enter annual salary and applicable deductions to compute total tax liability, including cess and rebate handling.

The calculator also compares both tax regimes and indicates the more beneficial option.

---

## Features

- Supports New and Old tax regimes
- Standard deduction handling
  - ₹75,000 (New Regime)
  - ₹50,000 (Old Regime)
- Section 80C deduction validation
- Section 80D deduction validation
- Section 87A rebate handling
- Health and Education Cess (4%)
- Automated regime comparison
- Detailed tax breakdown
- Dark and Light mode support
- Responsive user interface

---

## Tax Logic (FY 2024-25)

### New Regime Slabs

- 0 – 3,00,000: 0%
- 3,00,001 – 6,00,000: 5%
- 6,00,001 – 9,00,000: 10%
- 9,00,001 – 12,00,000: 15%
- 12,00,001 – 15,00,000: 20%
- Above 15,00,000: 30%

Rebate available under Section 87A up to ₹7,00,000.

---

### Old Regime Slabs

- 0 – 2,50,000: 0%
- 2,50,001 – 5,00,000: 5%
- 5,00,001 – 10,00,000: 20%
- Above 10,00,000: 30%

Rebate available under Section 87A up to ₹5,00,000.

---

## Calculation Components

- Gross Salary
- Standard Deduction
- Section 80C Deduction
- Section 80D Deduction
- Taxable Income
- Income Tax as per slab
- Health and Education Cess (4%)
- Total Tax Payable
- Regime comparison output

---

## Tech Stack

- HTML5
- CSS3 (CSS Variables for theming)
- Vanilla JavaScript
- Intl.NumberFormat API for currency formatting

---

## Project Structure

fy2024-25-income-tax-calculator/
│
├── index.html
├── README.md

---

## Disclaimer

This calculator is intended for educational and demonstration purposes only. Tax calculations are based on FY 2024-25 slab rates and may change as per government notifications. For official filing and compliance, consult a qualified tax professional.

---

## Author

Tamanna Sayyed  
© 2026 All Rights Reserved
