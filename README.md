## Appium Mobile Automation Framework
Implemented an Android mobile automation framework using Page Object Model that enhances maintainability, scalability, and collaboration in testing efforts. It promotes structured test design, improves test efficiency, and supports agile development practices by facilitating rapid feedback loops. By encapsulating UI interactions into reusable components (Page Objects), teams can achieve more reliable and maintainable automated tests across different Android devices and versions.

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Maven 3.6.3 or higher
- Android SDK
- Appium Server
- IDE (e.g., IntelliJ IDEA, Eclipse)
- Node.js (for Appium server)

## Getting Started
### Installation
1. **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/your-repo-name](https://github.com/SoundharyaB/Java-Appium-Android-Page-Object-Model-Framework.git
    cd your-repo-name
    ```
2. **Install dependencies:**
    Ensure you have all the necessary dependencies installed by running:
    ```bash
    mvn clean install (or above Prerequisites)

**## Run test suite/specific tests:**
    You can also run specific test suites by specifying the suite XML file:
    ```bash
    mvn test -DsuiteXmlFile=testng.xml
    ```

## Project Structure
As in above with below functions
- src/main/java - Object repos, utils
- src/main/test - Test Scripts
- src/main/java/resources - GS.apk file and data properties file
- reports - index.html extent test reports
- reportsFillForm.png - Screenshot captured while execution


## Framework Advantages
1. Modularity and Reusability with Enhanced Readability and Maintainability:
2. Clear Structure supports easier to understand, modify and Simplified Debugging/quicker troubleshooting.
3. Improved Test Design and Scalability.
4. Parallel Execution and Efficiency to Identify UI issues early in the development cycle and reduce time-to-market.
5. Collaboration and Documentation facilitates collaboration between testers and developers and Acts as living documentation of the application’s UI structure and functionality.


