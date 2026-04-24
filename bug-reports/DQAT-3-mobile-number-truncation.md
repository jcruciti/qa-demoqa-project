# DQAT-3 - Mobile Number Field Truncates Input

## Description
Mobile Number field truncates input when more than 10 digits are entered.

## Steps to Reproduce
1. Open Practice Form page
2. Enter mobile number: 5511998366890
3. Observe input field behavior
4. Click Submit

## Expected Result
System should enforce defined length constraint or clearly validate input (10 digits or defined requirement)

## Actual Result
Field truncates input to first 10 digits (5511998366)

## Severity
Medium

## Priority
High

## Environment
- Browser: Chrome
- URL: https://demoqa.com
