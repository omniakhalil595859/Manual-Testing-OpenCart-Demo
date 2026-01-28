# Make Test

## Table of Contents
- [Introduction](#introduction)
- [Test Scenarios](#test-scenarios)
- [Bug Report](#bug-report)
- [Test Execution](#test-execution)


## Introduction
Make Test is a comprehensive testing framework designed to streamline the process of creating, executing, and reporting on tests. This README provides guidelines on how to document test scenarios, report bugs, and execute tests effectively.

## Test Scenarios
Test scenarios outline the conditions under which tests will be executed. Each scenario should include:

- **Scenario ID**: Unique identifier for the scenario.
- **Title**: A brief description of the scenario.
- **Preconditions**: Conditions that must be met before executing the scenario.
- **Test Steps**: Step-by-step instructions on how to perform the test.
- **Expected Result**: The expected outcome of the test.

### Example Test Scenario
| Scenario ID | Title                   | Preconditions          | Test Steps                           | Expected Result                |
|-------------|-------------------------|------------------------|--------------------------------------|---------------------------------|
| TC001       | User Login              | User is registered     | 1. Open login page                   | User is redirected to dashboard |
|             |                         |                        | 2. Enter valid credentials           |                                 |
|             |                         |                        | 3. Click login button                |                                 |

## Bug Report
A bug report should provide detailed information about any defects encountered during testing. Each report should include:

- **Bug ID**: Unique identifier for the bug.
- **Title**: A brief description of the bug.
- **Description**: Detailed explanation of the issue.
- **Steps to Reproduce**: Instructions to replicate the bug.
- **Expected Result**: What was expected to happen.
- **Actual Result**: What actually happened.
- **Severity**: Impact level of the bug (e.g., Critical, Major, Minor).
- **Status**: Current status of the bug (e.g., Open, In Progress, Resolved).

### Example Bug Report
| Bug ID | Title               | Description                | Steps to Reproduce                     | Expected Result                | Actual Result            
|--------|---------------------|----------------------------|----------------------------------------|--------------------------------|----------------------------
| BUG001 | Login Failure       | User cannot log in         | 1. Go to login page                   | User should log in successfully | Error message displayed    |

## Test Execution
Test execution involves running the test scenarios and documenting the results. Follow these steps:

1. **Prepare the Test Environment**: Ensure all necessary tools and environments are set up.
2. **Execute Test Scenarios**: Run each scenario as per the defined test steps.
3. **Document Results**: Record the outcomes of each test, including pass/fail status.
4. **Log Bugs**: If any issues are encountered, log them using the bug report format.
5. **Review Results**: Analyze the results to identify patterns or areas for improvement.

### Example Execution Log
| Scenario ID | Execution Date | Status | Comments                          |
|-------------|----------------|--------|-----------------------------------|
| TC001       | 2025-01-15     | Passed | All steps executed successfully.  |
| TC002       | 2025-01-15     | Failed | Bug found: Login Failure (BUG001) |

