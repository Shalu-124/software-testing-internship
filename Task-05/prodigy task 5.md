## **Task-05: Automation Testing for E-Commerce Demo Website**

### **Objective**

        The objective of this task is to understand and analyze how an end-to-end e-commerce flow can be automated using Playwright. This task focuses on observing the application behavior and defining an automation approach based on real-time website conditions.

### **Tools & Framework**

* Playwright (same framework used in Task-03 and Task-04)

* Node.js

* Demo E-commerce Website provided in the task

**Note:-**

No new automation scripts were executed for this task. The focus was on understanding the flow and identifying testable scenarios.

### 

### **Website Understanding & Manual Observation**

The demo e-commerce website was explored to understand the overall user flow. The following observations were made:

* Product listing page loads successfully

* Product names and prices are displayed correctly

* Navigation between pages works as expected

* All products are marked as **out of stock**

* Add to Cart buttons are visible, but checkout/payment flow is not available

Due to these limitations, a complete purchase flow could not be performed.

### **Identified Issues / Limitations**

1. **All products are out of stock**, so checkout and payment options are not available

2. **End-to-end purchase flow cannot be completed**

3. **Google Maps section on the website does not load**, indicating a broken or missing integration

These issues appear to be limitations of the demo website rather than functional failures.

### **Automation Approach (Planned using Playwright)**

If automation were to be implemented, the following steps would be followed:

1. Launch the demo website using Playwright

2. Verify product listing page and product visibility

3. Validate product names and prices

4. Check Add to Cart button availability and behavior

5. Navigate to the cart page

6. Verify that checkout/payment options are unavailable due to out-of-stock products

7. Validate page navigation and UI consistency

8. Log identified limitations instead of failing the test

This approach ensures that the automation script handles real-world limitations gracefully.

### 

### 

### **Observations**

* Website navigation works smoothly

* UI elements are mostly functional

* Pricing information is displayed correctly

* Demo limitations restrict full checkout testing

* External integration (Google Maps) is not functioning

### **Conclusion**

Through this task, I gained a clear understanding of how automation testing is planned even when a website does not support a complete end-to-end flow. Instead of forcing failures, application limitations were identified and documented.

This task helped me understand how testers analyze real-time issues, handle incomplete demo applications, and design automation strategies using Playwright based on actual website behavior

