# Swag Labs - Manual QA Testing Project

## Project Overview
This project demonstrates manual QA testing of the Swag Labs e-commerce application (https://www.saucedemo.com). The testing focused on verifying the core user journey: login, product browsing, cart functionality, and checkout process.

## Objectives
- Validate the "happy path" customer journey works correctly
- Identify and document bugs using different test user accounts
- Create professional test documentation following industry standards
- Demonstrate manual testing skills for a Junior QA role

## Testing Scope

### In Scope:
- User login functionality (positive and negative scenarios)
- Product page display and navigation
- Add to cart functionality
- Shopping cart page verification
- Complete checkout flow (information entry, review, order completion)
- User logout functionality

### Out of Scope:
- Social media links
- About page
- Password reset functionality
- Performance testing beyond basic observation

## Test Approach
1. **Requirements Analysis** - Understood core user flows and business-critical features
2. **Test Case Design** - Created 6 detailed test cases covering positive and negative scenarios
3. **Test Execution** - Executed all test cases systematically and documented results
4. **Bug Reporting** - Tested with problem_user account to identify and document bugs
5. **Test Summary** - Compiled findings and recommendations

## Test Results Summary
- **Total Test Cases:** 6
- **Test Cases Passed:** 6
- **Test Cases Failed:** 0
- **Pass Rate:** 100%
- **Bugs Found:** 2 (1 Major, 1 Minor)

## Key Findings
The core functionality for the standard_user account works perfectly with 100% test pass rate. However, testing with the problem_user account revealed:

1. **BUG-001 (Major):** Product images display incorrectly - all products show the same image instead of unique product photos
2. **BUG-002 (Minor):** Add to cart button has delayed response, creating poor user experience

## Recommendation
The application is production-ready for standard users. The problem_user account issues should be addressed in the next sprint to ensure consistent experience across all user accounts.

## Tools Used
- **Browser:** Chrome (latest stable version, 2024-2026)
- **Test Management:** Google Sheets
- **Screenshot Tool:** Windows Snipping Tool / Mac Screenshot
- **Documentation:** Markdown (README.md)

## Deliverables
- `Swag-Labs-Test-Cases.pdf` - Detailed test cases with steps and expected results
- `Swag-Labs-Bug-Reports.pdf` - Professional bug reports with reproduction steps
- `Swag-Labs-Test-Summary.pdf` - Executive summary with metrics and recommendations
- `README.md` - This project documentation

## Skills Demonstrated
- Manual test case writing
- Test execution and result documentation
- Bug identification and reporting
- Severity classification
- Clear communication of test results
- Understanding of QA best practices
- Familiarity with e-commerce application testing

## About This Project
This project was completed as part of building a QA portfolio to demonstrate manual testing capabilities for Junior QA positions. All testing was performed independently following industry-standard QA practices.

---

**Application Tested:** Swag Labs (https://www.saucedemo.com)  
**Test Date:**10 January 2026  
**Tester:** [Oshini Poornima]