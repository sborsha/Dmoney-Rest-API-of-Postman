# Project Title: Demoney API automation Using with Automation and generate report using Newman
# Also Test Case of standard test case format for the Dmoney Rest API and Bug Report

## Project Summary: In this project- 
  1. Admin creates an agent and random 2 customers.
  2. Deposit some money from SYSTEM account to the agent. System account: SYSTEM (range 10 tk to 10000 tk)
  3. Agent deposit to any of 1 customer
  4. Check agent balance
  5. Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
  6. Then the customer checks balance
  7. Then send money to the other customer
  8. Then from the another customer payment to merchant
  9. Then the second customer will check both balance and statement
  10. Then the merchant will check his own balance

## Prerequisities:
1. install node.js
## How to run
1. Clone this project
2. Give following commands
   ```npm i```
   ```npm start```
## Output Newman reprt:
![newman report](https://github.com/sborsha/Dmoney-Rest-API-of-Postman-/assets/97577812/80126e6e-7fd1-4c32-ae61-f60dfdf5ebc3)

API Documentation of Postman: https://documenter.getpostman.com/view/32621543/2s9Yywez6f

## Test case execl fle: https://docs.google.com/spreadsheets/d/1G2vTgs6ePagMx9DdOGqwr6ZvjuRljFkw/edit?usp=sharing&ouid=117539685062847307961&rtpof=true&sd=true
