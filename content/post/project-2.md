---
date: 2024-01-04
description: "A compound interest calculator web application allowing the user to understand how their savings and investment account balances can grow with the magic of compound interest. This web application can be locally deployable using Streamlit."
featured_image: "/images/savings_photo.jpg"
tags: ["finance"]
title: "Compound Interest Calculator"
---

**Compound Interest Equation Used:**

![](https://sqy7rm.media.zestyio.com/Compound-Interest-Formula-Mobile.png)

The inspiration for this user interactive calculator was based on https://www.nerdwallet.com/calculator/compound-interest-calculator.

I wanted to create this calculator to learn how compound interest works rather than simply plugging in the numbers into a website.

This web application allows the user to adjust the same parameters as on the website:
* Initial deposit
* Contribution amount
* Contribution frequency
* Years of growth
* Estimated rate of return

It also shows a scatter plot showing the total balance after each year with and without compound interest.

Adjusting any of the parameters will automatically adjust the results in the figure.

This web application was built in Python using the following libraries:
* streamlit
* pandas
* plotly

This web application can be run locally by performing the following command in the terminal:
``` bash
streamlit run https://github.com/kthuang20/CompoundInterestCalc/blob/master/interest_calc.py
```

[Link to GitHub Repository](https://github.com/kthuang20/CompoundInterestCalc)
