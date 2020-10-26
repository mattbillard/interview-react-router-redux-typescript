# InRhythm Coding Challenge
The purpose of this challenge is to test your skills in technologies that are used heavily on the project that you are a candidate for.  It will focus on building out a simple application using React, Redux and TypeScript.  This is an open ended interview, and there is no set amount that needs to be done in the allotted time.  We don't expect you to have every bit of JS syntax memorized, so feel free to use google/stack overflow when you are stuck.

Most of all we just want to see how you code.  Good luck!

# Instructions

### Setup
1. Clone the [repository](https://github.com/mattbillard/interview-react-router-redux-typescript) (you will need to be granted permission first)
2. Create a branch called `YYYY/MM/DD-your-name` using today's date and your first and last name.

---
### Part A
You are tasked with creating a simple financial data application.  Users should be able to type a ticker from the list of valid tickers (below) and see the associated data.

**Key features:**
* Make a text input and submit button (unstyled)
* Clicking submit should call the API `/overview/` endpoint of data API according the ticker typed in the text input
* Store the return data in Redux

Example endpoint:
`/api/overview/MSFT.json`

### Valid Tickers
```
AAPL
ADBE
AMZN
AVGO
CMCSA
CRM
CSCO
FB
IBM
INTC
MA
MSFT
NFLX
NVDA
ORCL
PYPL
T
TXN
V
VZ
```

---

### Part B

Now that you have the data, create a table to display it in the UI.

**Key features:**
* Each company should have its own row (you can pick which columns)
* Each row should have a button to delete it from the UI and Redux store

---
### Part C 

At this point you and your interviewer will pick additional functionality to add (provided there is enough time).  Choices include:
* CSS styling
* Adding a UI library
* Form validation & error notifications
* UI/UX improvements of your choice
* Adding links to balance sheet, cashflow, and income statement information (can be displayed on a new page, modal, etc)
* Improve type safety of the application
