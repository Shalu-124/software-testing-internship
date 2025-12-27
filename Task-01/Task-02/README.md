Task-02: Compatibility Testing for Basic Web Page

Website Tested
E-commerce Demo Website (Shoplane)

Test Environment

Browsers Tested
Google Chrome (Desktop)

Devices Tested
Desktop
Mobile (Chrome DevTools – Responsive View)

Overview
Compatibility testing was performed to verify whether the website functions and appears consistently across different views. The focus was on layout behavior,
navigation links, header functionality, and basic user actions such as browsing and placing orders.

Test Findings

TC_001:
Verify website behavior on Chrome Desktop

Expected Result:
Website should load properly and allow smooth navigation

Actual Result:
Website loads successfully and scrolls smoothly without any visual break

Status:
“Pass”

TC_002:
Verify header navigation – Clothing menu

Expected Result:
Clicking on the Clothing menu should redirect to the relevant product page

Actual Result:
Clothing menu does not respond when clicked

Status:
“Fail”

TC_003:
Verify header navigation – Accessories menu

Expected Result:
Accessories menu should open the accessories product page

Actual Result:
Accessories menu redirects to a “404 Page Not Found” screen

Status:
“Fail”

TC_004:
Verify header search bar functionality

Expected Result:
Search bar should allow users to search for products

Actual Result:
Search bar is visible but does not perform any search action

Status:
“Fail”

TC_005:
Verify Add to Cart and order placement functionality

Expected Result:
Products should be added to cart and orders should be placed successfully

Actual Result:
Add to Cart and order placement features work correctly

Status:
” Pass”

TC_006:
Verify footer navigation and informational links

Expected Result:
Footer links such as Home, About, Products, Contact, and Address details
should be accessible

Actual Result:
Footer links are visible but do not respond when clicked
Status:
“Fail”

TC_007:
Verify responsiveness on mobile view

Expected Result:
Website should adapt properly to mobile screen sizes without layout issue

Actual Result:
Website adjusts correctly to mobile view with no overlap or horizontal scrolling

Status:
“Pass”

Issues Identified
1. Clothing menu in the header is not functional
2. Accessories menu leads to a 404 Page Not Found error
3. Header search bar does not work
4. Footer links (Home, About, Products, Contact, Address details) are not clickable

Recommendations

Fix non-functional header navigation links (Clothing and Accessories)
Resolve broken route causing the 404 error for Accessories page
Implement proper search functionality in the header search bar
Enable footer links to improve accessibility and user trust
Perform additional cross-browser testing to ensure consistent behavior
Conclusion

The website performs well in terms of layout responsiveness and order placement functionality across desktop and mobile views. However, several navigation and usability issues were identified in the header and footer sections. Addressing these issues will significantly enhance the overall user experience and compatibility of the website.
