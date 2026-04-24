# DQAT-4 - File Upload Accepts Invalid File Types

## Description
File upload field accepts any file type without validation.

## Steps to Reproduce
1. Open Practice Form page
2. Upload a non-image file (.pdf, .txt, .exe)
3. Click Submit

## Expected Result
System should accept only valid image formats (.jpg, .jpeg, .png) and reject invalid file types

## Actual Result
System accepts any file type without validation or error message

## Severity
High

## Priority
High

## Environment
- Browser: Chrome
- URL: https://demoqa.com
