# Testing Strategy

This project uses a combination of unit testing and integration testing to ensure the correctness of the calculator application.

Unit tests verify that individual functions work correctly in isolation. These tests check each arithmetic operation independently.

Integration tests verify that different parts of the system work together correctly, simulating a simple user interaction flow.

## Testing Pyramid

The testing strategy follows the Testing Pyramid concept. The majority of tests are unit tests because they are fast and reliable. Only a small number of integration tests are included to verify system behavior.

## Black-box vs White-box Testing

Unit tests in this project follow a white-box testing approach because they test internal functions directly.

Integration tests follow a black-box approach because they verify the overall behavior of the application without focusing on internal implementation.

## Functional vs Non-Functional Testing

This project focuses on functional testing, ensuring that each calculator operation produces the correct result.

Non-functional aspects such as performance and security are not tested because they are outside the scope of this simple application.

## Regression Testing

The existing test suite can be used as regression tests. Whenever the code is updated in the future, running the test suite will ensure that previously working functionality is not broken.

## Test Results Summary

===================== test session starts =====================
platform win32 -- Python 3.10.11, pytest-9.0.2, pluggy-1.6.0
rootdir: C:\Users\pelin\Projects\swe-testing-assignment
plugins: anyio-3.7.1
collected 10 items                                             

swe-testing-assignment\integration_test.py ..            [ 20%]
swe-testing-assignment\test_calculator.py ........       [100%]

===================== 10 passed in 0.05s ======================





| Test Name | Type | Result |
|-----------|------|-------|
| test_add  | Unit | Pass |
| test_subtract | Unit | Pass |
| test_multiply | Unit | Pass |
| test_divide | Unit | Pass |
| test_divide_by_zero | Unit | Pass |
| test_negative_numbers | Unit | Pass |
| test_decimal_numbers | Unit | Pass |
| test_large_numbers | Unit | Pass |
| test_full_calculation_flow | Integration | Pass |
| test_clear_function | Integration | Pass |