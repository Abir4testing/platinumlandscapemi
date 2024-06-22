# Platinum Landscape MI Website Testing Report

The testing process for the website [https://platinumlandscapemi.com](https://platinumlandscapemi.com) involved functional, usability, and performance testing. Various test cases were executed to verify the functionality of website features, check for bugs, and assess the performance. The testing was conducted in a Windows 11 environment using Google Chrome versions 126.0.6478.114 and 126.0.6478.115 on 18 June 2024.

## List of Test Cases Executed

1. **Test Case ID: TC01**
   - **Title:** Verify navigation from home page to About page
   - **Status:** PASS

2. **Test Case ID: TC02**
   - **Title:** Verify navigation from home page to Residential page
   - **Status:** PASS

3. **Test Case ID: TC03**
   - **Title:** Verify navigation from home page to Commercial page
   - **Status:** PASS

4. **Test Case ID: TC04**
   - **Title:** Verify navigation from home page to Project page
   - **Status:** PASS

5. **Test Case ID: TC05**
   - **Title:** Verify navigation from home page to Contact page
   - **Status:** PASS

6. **Test Case ID: TC06**
   - **Title:** Verify navigation to Free Quote Button
   - **Status:** PASS

7. **Test Case ID: TC07**
   - **Title:** Verify navigation from home page to Terms and Conditions page
   - **Status:** PASS

8. **Test Case ID: TC08**
   - **Title:** Verify navigation from home page to Privacy Policy page
   - **Status:** PASS

9. **Test Case ID: TC09**
   - **Title:** Verify navigation from home page to Facebook link
   - **Status:** PASS

10. **Test Case ID: TC10**
    - **Title:** Verify navigation from home page to Instagram link
    - **Status:** PASS

11. **Test Case ID: TC11**
    - **Title:** Verify navigation from home page to LinkedIn link
    - **Status:** FAIL

12. **Test Case ID: TC12**
    - **Title:** Verify navigation from home page to YouTube link
    - **Status:** FAIL

13. **Test Case ID: TC13**
    - **Title:** Verify navigation to Contact Us (call icon beside the phone number)
    - **Status:** PASS

14. **Test Case ID: TC14**
    - **Title:** Verify subscription using a valid email
    - **Details:**
      - **Email Used:** sadia.mehzabin2019@gmail.com
      - **Expected Result:** Successfully submitted email message
      - **Actual Result:** Successfully submitted email message
    - **Status:** PASS

15. **Test Case ID: TC15**
    - **Title:** Verify subscription using an invalid email
    - **Details:**
      - **Email Used:** email@example.web
      - **Expected Result:** No successfully submitted email message
      - **Actual Result:** Successfully submitted email message
    - **Status:** FAIL

## Details of Bugs or Issues Found

1. **Bug Report 01**
   - **Title:** Subscription with invalid email
   - **Description:** The user is able to subscribe using an invalid email address.
   - **Steps to Reproduce:**
     1. Go to the URL [https://platinumlandscapemi.com](https://platinumlandscapemi.com)
     2. Navigate to the bottom of the website
     3. Click on the email address option and enter the email address `email@example.web`
     4. Press the enter button
   - **Environment:** Windows 11, Google Chrome 126.0.6478.114/115
   - **Severity:** Major
   - **Priority:** High
   - **Status:** Fail
   - **Reported By:** Sadia Mehzabin
   - **Date/Time:** 21/06/2024
   - **Comments:** The bug needs to be fixed ASAP.

2. **Bug Report 02**
   - **Title:** The user not able to navigate from home page to YouTube link
   - **Description:** The user is unable to navigate to the YouTube link from the home page.
   - **Steps to Reproduce:**
     1. Go to the URL [https://platinumlandscapemi.com](https://platinumlandscapemi.com)
     2. Navigate to the bottom of the website
     3. Click on the YouTube icon
   - **Environment:** Windows 11, Google Chrome 126.0.6478.114/115
   - **Severity:** Major
   - **Priority:** Medium
   - **Status:** Fail
   - **Reported By:** Sadia Mehzabin
   - **Date/Time:** 21/06/2024
   - **Comments:** The bug needs to be fixed.

3. **Bug Report 03**
   - **Title:** Call icon JavaScript popup behavior
   - **Description:** After the user clicks the call icon, the JavaScript popup cannot be removed.
   - **Steps to Reproduce:**
     1. Go to the URL [https://platinumlandscapemi.com](https://platinumlandscapemi.com)
     2. Navigate to the bottom of the website
     3. Click on the call icon beside the number +1 5868715330
     4. Observe the behavior
   - **Environment:** Windows 11, Google Chrome 126.0.6478.114/115
   - **Severity:** Major
   - **Priority:** High
   - **Status:** Fail
   - **Reported By:** Sadia Mehzabin
   - **Date/Time:** 21/06/2024
   - **Comments:** The bug needs to be fixed ASAP.

4. **Bug Report 04**
   - **Title:** The user is able to Subscribe by using invalid email
   - **Description:** The user can subscribe using an invalid email address.
   - **Steps to Reproduce:**
     1. Go to the URL [https://platinumlandscapemi.com](https://platinumlandscapemi.com)
     2. Navigate to the bottom of the website
     3. Click on the email address option and enter the email address `email@example.web`
     4. Press the enter button
   - **Environment:** Windows 11, Google Chrome 126.0.6478.114/115
   - **Severity:** Major
   - **Priority:** High
   - **Status:** Fail
   - **Reported By:** Sadia Mehzabin
   - **Date/Time:** 21/06/2024
   - **Comments:** The bug needs to be fixed ASAP.

## Performance Testing

### GTmetrix Report Summary:

- **Performance Score:** 48%
- **Structure Score:** 75%
- **Largest Contentful Paint (LCP):** 5.5s
- **Total Blocking Time (TBT):** 560ms
- **Cumulative Layout Shift (CLS):** 0
- **Total Page Size:** 1.89MB
- **Total Page Requests:** 175

### Top Issues:

1. Reduce initial server response time
2. Avoid enormous network payloads
3. Reduce JavaScript execution time
4. Serve static assets with an efficient cache policy
5. Avoid an excessive DOM size

## Suggestions for Improvements

1. **Improve Subscription Validation:**
   - Implement proper email validation to ensure only valid email addresses are accepted during subscription.

2. **Fix Call Icon JavaScript Popup:**
   - Review and debug the JavaScript handling the call icon to ensure the popup can be properly dismissed.

3. **Fix Navigation to YouTube Link:**
   - Ensure that the YouTube link is correctly set up and functional.

4. **Performance Enhancements:**
   - **Reduce Server Response Time:** Optimize server performance to decrease the time taken to load the initial HTML document.
   - **Minimize Network Payloads:** Compress and optimize images and other resources to reduce the total size of the network payload.
   - **Optimize JavaScript Execution:** Refactor and optimize JavaScript code to reduce the total blocking time and improve page load performance.
   - **Efficient Caching:** Implement caching strategies for static assets to reduce the load on the server and improve repeat visit load times.
   - **Reduce DOM Size:** Simplify the DOM structure to enhance rendering performance.
