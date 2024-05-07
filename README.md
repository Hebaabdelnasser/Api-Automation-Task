# Api-Automation-Task
This is an API automation testing framework built with Rest Assured, Java, TestNG, and Allure as the reporting tool.
Certainly! Here's an example of a README file for an API automation testing framework built with Rest Assured, Java, TestNG, and Allure as the reporting tool:

# API Automation Testing Framework

This is an API automation testing framework built with Rest Assured, Java, TestNG, and Allure as the reporting tool.

## Prerequisites

To run the tests in this framework, ensure that you have the following software installed:

- Java Development Kit (JDK) 8 or higher
- Apache Maven
- TestNG
- Allure Command Line (for generating Allure reports)

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/your-username/api-automation-framework.git
   ```

2. Navigate to the project directory:

   ```
   cd api-automation-framework
   ```

3. Install project dependencies:

   ```
   mvn clean install
   ```

## Running the Tests

To execute the tests, you can use a TestNG XML file. Follow these steps:

Open the testng.xml file located in the project root directory.
Configure the TestNG suite file according to your test requirements, including the test classes or test groups you want to run.

The tests will run using the Rest Assured framework and generate test reports in the `target/allure-results` directory.

## Generating Allure Reports

To generate and view Allure reports:

1. Make sure you have Allure Command Line installed on your system.
2. Run the following command to generate the Allure report:

allure serve
   ``
## Test Reports

This framework utilizes Allure as the reporting tool. After running the tests and generating the Allure report, you can view detailed test reports with rich visual representations, including graphs and statistics.


## Contact

If you have any questions or need further assistance, feel free to contact the project maintainers at [hebanasser996@gmail.com].

Feel free to modify and customize this template to suit your specific project requirements.
