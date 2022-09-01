# Book-API-Load-Test
#Book-API-Load-Test by Jmeter
#### **Question**

- Find out the actual TPS for if 10000 user can give load within 1 hour **Expected load:** 10000 user, per hour.
- **Actual load:** what TPS? Breakdown the expected TPS in excel sheet and find out the actual TPS.
- For 60s, 300s and 600s load, add Jmeter UI screenshot and for 900s generate html report and take screenshot.

##### **Solved**
- #### [**Excel and Word Report**](https://github.com/Tonmoy61/Book-API-Load-Test/tree/main/resources)

#### **Load Test Strategy**

- [Server](https://demoqa.com/BookStore/v1/Books)
| ![TPS Report](./Images/TPS_REPORT.png) |
| :------------------------------------: |
|              _Actual TPS_              |

#### **JMeter Summary Report**
- 60 Second, For 167 User.
| ![Test Case 1](./Images/TEST 1.png) |
| :----------------------------------:|
|                                     |

- 300 Second, For 834 User.
| ![Test Case 2](./Images/TEST 2.png) |
| :----------------------------------:|
|                                     |
-600 Second, for 1667 User.
| ![Test Case 3](./Images/TEST 3.png) |
| :----------------------------------:|
|                                     |

- Test Summary Report - 2500 users for 950 seconds

| ![Test Summary Report](./Images/REPORT.png) |
| :------------------------------------------: |
|               _Summary Report_               |
