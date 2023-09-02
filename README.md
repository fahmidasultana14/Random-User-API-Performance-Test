# Random-User-API-Performance-Test

## About this project:
###  In this project I have done load testing and stess testing using jmeter on some random user . Here I have counteded expected and actual TPS through load testing and bottleneck/stress test point through stress testing.


## Tools & Technology used:
- jmeter
  

## Prerequisite
- JDK or Java Development Kit
  
## How to run:
- Clone this project
- put the jmx file the bin folder of the jmeter installation path
- open cmd and hit the following command ```jmeter```
- from jmeter open the file from the bin and hit the run button


## Test Report
![screencapture-file-F-Road-to-sdt-apache-jmeter-5-6-2-bin-Report1-index-html-2023-09-02-10_40_05](https://github.com/fahmidasultana14/Random-User-API-Performance-Test/assets/101444545/19667f87-489a-4b7a-8d85-f2f8364f31c7)



## Load Test Report
![load-test](https://github.com/fahmidasultana14/Random-User-API-Performance-Test/assets/101444545/2f46b3db-a527-4a98-86d4-6580c0dfbbd9)

##  Load Test Scenario:
In this load testing report conducted on the Random User API, the primary objective was to attain a targeted Transactions Per Second (TPS) rate of 2.78. The initial test encountered an error when the user count reached 1667 during a 10-minute test duration. To address this issue, the test duration was extended by an additional 50 seconds while maintaining a consistent user count, resulting in a reduction in errors. Subsequent tests encountered intermittent errors. To mitigate these, the user count remained constant while the test duration was incrementally extended. Ultimately, in Test-7, the test executed error-free; however, the achieved actual TPS stood at 2.3, which is below the initial target.


## Stress test Report
![stress test](https://github.com/fahmidasultana14/Random-User-API-Performance-Test/assets/101444545/ba4319f4-da8a-4514-8e1f-0e7b72b0c9ed)

##  Stress Test Scenario:
In this  Stress Testing Report conducted on the Random User API, the primary objective was to ascertain the system's bottleneck or stress test point. As the actual TPS was found for 1100 second test duration ,so this time was fixed. In the pursuit of identifying the stress point, a systematic approach was taken, where the user count was incrementally increased.
The first bottleneck was encountered when the total user count reached 45,000. Subsequently, an attempt was made to alleviate the stress by reducing the user count to 35,000; however, errors persisted. A further reduction to 25,000 users proved to yield error-free results. To refine the stress point, the user count was subsequently increased to 26,000, ultimately revealing a 1 percent error rate in the system.



