# demo-transaction-api-jmeter

## project Summary:
This project has automate user API from jmeter

## Technology used:
- Apache jmeter


## Pre-requisites:
- JDK

## Scenario: 
Based on following scenario, creating a JMX file with positive test case based on this flow.
- Admin creates an agent and a customer
- Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
- Deposit 1000 tk to customer from agent account
- Check balance from customer account
- Withdraw 500 tk from customer account
- Payment 200 tk from customer account (Merchant account: 01686606905)
- Assert expected customer balance
- Generating html report based on the above scenario

## API Documentation:
User documentation:
You will get the user API URL, endpoint, header info and demo data from here:
https://documenter.getpostman.com/view/1844288/UzBiQpVN

Transaction documentation:
You will get the transaction API URL, endpoint, header info and demo data from here:
https://documenter.getpostman.com/view/1844288/2s7YmzAhnk

## html Report:
![_C__Users_sayma_Downloads_apache-jmeter-5 5_bin_Reports_index html](https://github.com/Sayma-Mahjuba/demo-transaction-api-jmeter/assets/67679589/ece7b3c0-e06b-4522-b066-016af4d4efff)

![_C__Users2_sayma_Downloads_apache-jmeter-5 5_bin_Reports_content_pages_OverTime html](https://github.com/Sayma-Mahjuba/demo-transaction-api-jmeter/assets/67679589/2efba9ed-393c-4166-9ede-6f3c0b79ca8b)


![_C__Users3_sayma_Downloads_apache-jmeter-5 5_bin_Reports_content_pages_CustomsGraphs html](https://github.com/Sayma-Mahjuba/demo-transaction-api-jmeter/assets/67679589/4988e64a-52a7-499c-aea6-586e5c544d5c)
