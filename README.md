# Random-User-API-Performance-Test

## About this project:
###  In this project I have done load testing and stess testing using jmeter on some random user . Here I have counteded expected and actual TPS through load testing and bottleneck/stress test point through stress testing.


## Tools & Technology used:
- jmeter
  

## Prerequisite
- JDK or Java Development Kit
  
## How to run:
- clone this project
- Give following command:
- ``` npm i ```
- ``` npm test ```


## Test Report
![screencapture-file-F-Road-to-sdt-apache-jmeter-5-6-2-bin-Report1-index-html-2023-09-02-10_40_05](https://github.com/fahmidasultana14/Random-User-API-Performance-Test/assets/101444545/19667f87-489a-4b7a-8d85-f2f8364f31c7)



## Load Test Report
https://docs.google.com/spreadsheets/d/15AREkVzivDXYFljaDRbohPbQ344cNMB9/edit?usp=sharing&ouid=103675646332830778644&rtpof=true&sd=true

##  Load Test Scenario:
In this load testing report conducted on the Random User API, the primary objective was to attain a targeted Transactions Per Second (TPS) rate of 2.78. The initial test encountered an error when the user count reached 1667 during a 10-minute test duration. To address this issue, the test duration was extended by an additional 50 seconds while maintaining a consistent user count, resulting in a reduction in errors. Subsequent tests encountered intermittent errors. To mitigate these, the user count remained constant while the test duration was incrementally extended. Ultimately, in Test-7, the test executed error-free; however, the achieved actual TPS stood at 2.3, which is below the initial target.


## Stress test Report
https://docs.google.com/spreadsheets/d/132iz8FIvaIRKHcRmhCVi0Gd5DeqV-f7N/edit?usp=sharing&ouid=103675646332830778644&rtpof=true&sd=true


