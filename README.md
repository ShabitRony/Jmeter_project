# JMETER PERFORMANCE TESTING
## Project Overview
- This repository contains JMeter test plans for performance testing for two scenarios.
# Task-1 : Performance testing for Booking API
## In this scenario 120,000 users over a 12-hour period can log in, create a booking, and search for the booking. 
- Total User : 120000 and Time Period 12 hours = 12*60*60 seconds = 43,200 seconds.
- Thoughput(Request per sceond): 120000/43200 = 2.78 request/second.
- Gaussian Random Timer(Deviation 2000ms, Constant delay 500ms).
### Conducted tests in 3 steps:
- 5 minute load test
- 10 minute load test
- 20 minute load test
## Load Test Step Report
![testreport1](https://github.com/user-attachments/assets/8652e7a4-1c36-48f3-9a8b-e2189ecdadb0)

## For 5 minute Summary Report 
![boking1](https://github.com/user-attachments/assets/c9ed6e03-f849-45d2-b678-2d3c92107d62)
## For 10 minute Summary Report 
![load2](https://github.com/user-attachments/assets/3898e9d8-b317-452a-981e-1596c332c08e)
## For 20 minute HTML Report 
![Jmeter load test report](https://github.com/user-attachments/assets/22d4c114-a1ec-4913-bc43-9703a9b6921e)
# Stress Test
- Gradually increase the load until the server start failing.
## Stress Test Step Report
[Performance-test.xlsx](https://github.com/user-attachments/files/19636816/Performance-test.xlsx)

## For 20000 user summary report
![stest1](https://github.com/user-attachments/assets/c2e01e67-8cdf-4a2c-a9d1-d8734e8b1ae5)
## For 23000 user summary report
![finaltest2](https://github.com/user-attachments/assets/4187a8d6-f4c0-4a69-ae74-5cc2b4828f50)
## For 25000 user summary report
  ![finaltest1](https://github.com/user-attachments/assets/ba6bca18-855f-4008-89b6-b85c7a90fda9)

# Stress Test HTML Report
![Finalstresstest](https://github.com/user-attachments/assets/7ac0bd39-d13f-4f49-9295-6f3cec8c663d)


# Load test and Stress test excel file 
[Performance-test.xlsx](https://github.com/user-attachments/files/19411688/Performance-test.xlsx)

# Task 2: Functional Testing for dmoney API
### Summary Report
![dmoneytest](https://github.com/user-attachments/assets/fc1dea4a-8525-4e0c-98c6-42d9baa5f20a)

### HTML Report
![jmeter_api_manipulation](https://github.com/user-attachments/assets/c936aba7-461f-46a8-8ff9-e804945f2ca6)

# Pre-reqisites
- Apache JMeter
- Clone this repository from GitHub
# How to run?
## Task 1
- Open Apache JMeter
- Open Booking.jmx file
- Run the test for the required time period
- View result in the HTML report
## Task 2
- Open dmoney.jmx file
- Placed the CSV file in the same directory
- Run the test
- Validate response assertions
- View result in the HTML report




