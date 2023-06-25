# API Automation Test BDD framework
API Automation Test is RestAssured based Cucumber framework to perform API testing. This project is useful as an example of API Testing with RestAssured and Java playing nicely together.

## Getting Started
```
1. git clone https://github.com/sadabnepal/APIRestasssuredBDDFramework.git"
2. Navigate to APIRestasssuredBDDFramework
```

**In terminal from root project folder (RestasssuredCucumber), run below commands as required**

Run Tests
- To run all features `mvn clean test verify`
- To pass environment variable from command line `mvn clean test verify -DargLine=-DWSNSHELL_HOME=RSURI`
  *RSRUI* is environment passed in `src-> test-> java-> base-> BaseBuilder.java` and defined in *config.properties*
  
Report Path  
- Cucumber HTML Report: `{ROOT_PROJECT_FOLDER}/target/cucumber-html-reports/overview-features.html`
- Spark Report: `{ROOT_PROJECT_FOLDER}/test-output/Pdf/ExtentPdf.pdf`
- Cucumber PDF Report: `{ROOT_PROJECT_FOLDER}/test-output/Spark/ExtentSpark.html`


### Key Features
	- Runtime environment set
	- Hashmap to simplify serialization of payload
	- Tag based execution
	- Detailed Cucumber Report
	- Header builder simplified
	- Reusable methods to perform GET, POST operations

## Sample Report
![Report](https://user-images.githubusercontent.com/65847528/102914715-b95be780-44a6-11eb-8022-79b9149c5fad.gif)
