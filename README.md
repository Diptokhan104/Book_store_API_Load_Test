# Bookstore_API_Load_Test_Using_Jmeter


# About this project

- In this project TPS(Transaction Per Second) 1250 user gave load via Bookstore API within 8 minute
-  Expected load: 1250 user, per hour.
-  For 480(second) load generate html report and screenshot taken.

# How to run this project
- Clone this project
- Bookstore_API_Load_Test_Using_Jmeter.get
- - cd Bookstore_API_Load_Test_Using_Jmeter
- Move file into \apache-jmeter-5.5\bin this path
- Open in windows terminal or git bash terminal and run below command
- - jmeter -n -t "BookAPILoadtest.jmx" -l "BookAPILoadtest.csv" -e -o Reports
 
# JMeter Summary Report

- Test Report Summary

  <img width="459" alt="Summary Report" src="https://github.com/Diptokhan104/Bookstore_API_Load_Test_Using_Jmeter/assets/29312905/bd493fd6-de77-466b-b0d3-9bc5dd707cb3">

- Over Time

  ![OverTime](https://github.com/Diptokhan104/Bookstore_API_Load_Test_Using_Jmeter/assets/29312905/e7e032f1-fa88-4250-a45e-4e02981a0d57)

- Throughput

  ![ThroughPut](https://github.com/Diptokhan104/Bookstore_API_Load_Test_Using_Jmeter/assets/29312905/f9a1ae3f-5720-4b84-835a-2908964df8ee)

- Response Times

  ![ResponseTime](https://github.com/Diptokhan104/Bookstore_API_Load_Test_Using_Jmeter/assets/29312905/477233d3-e8f9-4860-bedf-fb8256c1ddee)



