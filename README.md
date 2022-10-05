# Random-User-API-Performance-Test with Jmeter

## Technology and Tool used

- Jmeter
- Java jdk

## Scenario of this project

- Performing load test on the following URL: **https://random-data-api.com/api/v2/users**
-  Finding out if the expected TPS (Transaction Per/Second) meet the following requirement: **120000 user can give load for 12 hour**
- Breaking down the expected TPS in excel sheet and finding out the actual TPS
- Finding out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project

- Download the jmx file
- Run the file in Jmeter with the values from the excell sheets

## prerequisites
**You must have jdk and jmeter installed in your system**


## Excell Documents of Load and Stress Strategy
https://docs.google.com/spreadsheets/d/1r9g2BsrnQX9DDMomwgbOuY4tFF78dWwM/edit?usp=sharing&ouid=113984228926483049674&rtpof=true&sd=true

## Output

![Load](https://user-images.githubusercontent.com/54511128/194081506-d5b82f35-d128-4032-87d8-9edcd50b7f10.png)
![Capture](https://user-images.githubusercontent.com/54511128/194081632-3325722b-6a80-4f3c-85e6-f4a9c5b7b2ef.PNG)
![Stress](https://user-images.githubusercontent.com/54511128/194081665-55a8e69f-26d8-4ac2-862d-b97931c47319.png)
