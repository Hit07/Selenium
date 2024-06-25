# Automation Testing of Yahoo Signup Page using Selenium

This project involves automated testing of the Yahoo signup page using Selenium, a widely used open-source Web UI automation testing suite. TestNG is utilized for generating comprehensive test reports, enabling easy identification of passed, failed, and skipped test cases. This facilitates efficient debugging and re-execution of failed tests.

### Project Overview

The primary objective is to automate the testing of Yahoo's signup functionality to ensure robust performance and functionality across different scenarios. Selenium WebDriver is employed to simulate user interactions with the signup page, while TestNG provides structured test case management and detailed reporting capabilities.

### Getting Started

To run the tests locally, follow these steps:

1. **Clone the Repository:** ```git clone https://github.com/Hit07/Yahoo-Selenium.git```
2. 
2. **Setup Environment:**
- Ensure Java Development Kit (JDK) is installed.
- Download and configure Selenium WebDriver for Java.
- Download and configure TestNG.

3. **Run the Tests:**
- Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
- Update the path to the ChromeDriver executable in the test code (`yahoo.java`).
- Execute the tests by running the `yahoo.java` file as a TestNG test.

### Test Data

The test cases use a Data Provider (`create`) to supply various input combinations for testing Yahoo signup:
- First Name
- Last Name
- Email
- Password
- Date of Birth
- Phone Number

### Notes

- Ensure proper setup of Selenium WebDriver and TestNG configurations to execute the tests successfully.
- Adjust the XPath selectors in the test code (`yahoo.java`) as necessary based on any changes to the Yahoo signup page structure.



For detailed guidance on Selenium and TestNG, refer to their respective documentation:
- [Selenium Documentation](https://www.selenium.dev/documentation/en/)
- [TestNG Documentation](https://testng.org/doc/documentation-main.html)
