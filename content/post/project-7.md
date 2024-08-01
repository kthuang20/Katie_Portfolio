---
date: 2024-07-31
description: "A personal finance dashboard that analyzes your yearly spending habits and investments."
featured_image: "/images/finance-app.png"
tags: ["finance", "data science", "dashboard"]
title: "Finance App 💰"
---
## Objective
Developed a personal finance app to provide insights into users' spending, saving habits, and investments, guiding them towards their financial goals. Explore the app [here](https://finance-investment-app.streamlit.app).

## Inspiration
Managing multiple accounts across different platforms is challenging and time-consuming. Existing finance apps often require new accounts and can be costly. This inspired the creation of a finance app that consolidates financial data without additional costs or complications.

## Methodology
Integrated a simple way to download and analyze transactions and investments across all accounts, primarily using Fidelity. Users can upload files with up to a year's worth of data, and the app automatically generates a dashboard for analysis.

***Packages used:*** numpy, pandas, streamlit, plotly

## Key Features:
* *Spending Analysis:*
	* Bar charts for monthly expenses, income, and net gain.
	* Pie charts for spending categories and income types.
	* Summary statistics for average earnings, savings, and spending percentages.
* *Investment Analysis:*
	* Bar charts for monthly investments by ticker symbol and total investments.
	* Pie charts for investment types and dividends received.

## Limitations
The app was developed using data from Fidelity. While users can upload their own files, the data must be structured similarly to the provided examples. Fidelity users can follow the provided steps, while non-Fidelity users may need to adjust their data manually.

## Impact 
Enabled users to make informed financial decisions by understanding their spending and saving habits. The app helps users track their progress towards financial goals and adjust their habits if needed.


--- 
*Source code and sample files used in this app are available at:* https://github.com/kthuang20/finance-app