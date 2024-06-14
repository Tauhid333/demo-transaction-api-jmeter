# Dmoney API

## Problem Statement

Based on following scenario, create a JMX file. No need to create negative testing. Just create the positive test case based on this flow.
- Admin creates an agent and a customer
- Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
- Deposit 1000 tk to customer from agent account
- Check balance from customer account
- Withdraw 500 tk from customer account
- Payment 200 tk from customer account (Create any merchant acc or search any merchant for payment)


## Table of Contents

- [API Endpoints](#api_endpoints)
- [Tasks Performed](#tasks_Performed)
- [Results](#results)
  - [Screenshots](#screenshots)
  

## API Endpoints
- User documentation:
You will get the user API URL, endpoint, header info and demo data from here:
[https://documenter.getpostman.com/view/1844288/2s9YeABaGo](https://documenter.getpostman.com/view/1844288/2s9YeABaGo)

- Transaction documentation:
You will get the transaction API URL, endpoint, header info and demo data from here:
[https://documenter.getpostman.com/view/1844288/2s9YeABaGp](https://documenter.getpostman.com/view/1844288/2s9YeABaGp)

## Tasks Performed
- Admin logs in & creates 3 users with roles Agent, Customer, Merchant. We verify the response messages using assertions in Jmeter.
- System user logs in  and deposits to Agent account. We verify the response messages using assertions in Jmeter.
- Agent user logs in  and deposits to Customer account. We verify the response messages using assertions in Jmeter.
- Customer logs in & checks his balance. We verify the response messages using assertions in Jmeter.
- Customer withdraws money. We verify the response messages using assertions in Jmeter.
- Customer makes a payment to Merchant account. We verify the response messages using assertions in Jmeter.

## Results



### Screenshots
## Jmeter HTML Report
![Screenshot (478)](https://github.com/Tauhid333/demo-transaction-api-jmeter/assets/62515281/92a9402b-ab97-4528-8547-9da27f5f557c)
![Screenshot (479)](https://github.com/Tauhid333/demo-transaction-api-jmeter/assets/62515281/7ce54cfd-0168-463a-b70f-6525ef758756)







