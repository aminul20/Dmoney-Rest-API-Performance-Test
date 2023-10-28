# Dmoney Rest API Server Performance Test using Jmeter
This is a simple Load Testing project created using Jmeter on (DMoney) which is mainly an demo MFS API server.
Here user can do their financial transactions similar like Bkash.
First I have done All the tests manually and added test assertions for automation purpose according to the test cases which cover all the features of this API. Finally, I have generated report through CLI run.

## Prerequisite:
1. Java 8+ must be installed
2. Apache Jmeter must be installed & added to the Environment Variable

## How to run this project:
- Clone the repo
- Open cmd in the Project root folder
- Give the following command
```
jmeter -n -t dmoney_api.jmx -l Dmoney-Load-Test.csv -e -o Reports
```

## Technology used:
- Apache Jmeter v5.5

## CLI Run Report:
![]( https://i.imgur.com/8wUDkg8.png)

![]( https://i.imgur.com/rnD1Wai.png)
