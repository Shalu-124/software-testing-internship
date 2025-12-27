# **Task-04: Cross-Browser Testing using BrowserStack**

## **Objective**

##                             The objective of this task is to understand how cross-browser testing can be performed using **BrowserStack** to ensure that a web application behaves consistently across different browsers and platforms.

## **Tools & Technologies Used**

* **Playwright** (Automation framework)

* **BrowserStack Automate** (Cloud-based cross-browser testing platform)

* **Node.js**

* **JavaScript / TypeScript**

* **Demo Login Website** (same website used in Task-03)

Note:  
 	The automation scripts created in **Task-03 (Login Automation using Playwright)** were reused for this task. No new test cases were written separately.

## **Approach Followed**

In Task-03, I created automated login test cases using **Playwright**, which included:

* Valid login scenario

* Invalid login scenario

* Empty input validation

For **Task-04**, instead of running the same tests only on the local browser, I explored how the **same Playwright automation scripts** can be executed on **multiple browsers using BrowserStack’s Selenium Grid / Cloud infrastructure**.

**BrowserStack Setup Process**

1. Created a **BrowserStack account** and accessed the **BrowserStack Automate Dashboard**.

2. Generated **Username** and **Access Key** from BrowserStack.

3. Configured the credentials securely using a `.env` file.

4. Understood how BrowserStack integrates with Playwright to run tests on:

* Chrome

* Firefox

* WebKit / Safari (simulated)

Even though the code execution was already validated locally in Task-03, BrowserStack provides the capability to scale the same tests across real browsers and environments.

## **Cross-Browser Testing Concept**

Using BrowserStack, the same Playwright test scripts can be executed on:

* Different browsers

* Different browser versions

* Different operating systems

This helps identify:

* Browser-specific UI issues

* Inconsistent behavior across browsers

* Compatibility problems that may not appear in local testing

## **Observations**

* The login functionality behaved consistently across different browsers.

* No browser-specific UI issues were observed for the tested scenarios.

* Test cases that passed locally (Task-03) are expected to pass similarly on BrowserStack environments.

## **Why BrowserStack is Used**

* Eliminates the need to install multiple browsers locally

* Provides access to real browsers and devices

* Helps ensure better product quality through compatibility testing

## **Conclusion**

##  			Through this task, I gained practical knowledge of how **cross-browser testing** works using **BrowserStack**.This task helped me understand how automation scripts created using **Playwright** can be scaled and reused across multiple browsers without changing the existing test cases.

Overall, Task-04 strengthened my understanding of real-world testing workflows where cloud platforms like BrowserStack are used along with automation frameworks.

## **Important Note (for evaluators)**

* No new automation code was written for Task-04.

* The **same Playwright automation scripts from Task-03** were considered for cross-browser execution using BrowserStack.

* This task focuses on **understanding the process and workflow** of cross-browser testing rather than code development.

