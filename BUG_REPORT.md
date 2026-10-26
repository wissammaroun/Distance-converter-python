Bug Report — Distance Converter

Bug ID: BUG-001

Title: Negative values are accepted as valid distance
Severity: Medium
Priority: Medium
Status: Under Investigation

Steps to Reproduce

1. Open the application.
2. Enter -5 in the input field.
3. Select a conversion, such as KM to Miles.
4. Click Convert.

Expected Result

If negative distances are not allowed by the requirements, the application should display a clear validation message.

Actual Result

The application converts -5 and displays a negative result (for example, approximately -3.1 miles).

Notes

The requirement for negative input must be clarified before confirming this behavior as a defect.

⸻

Bug ID: BUG-002

Title: Non-numeric input may cause an application error
Severity: To Be Confirmed
Priority: To Be Confirmed
Status: Needs Verification

Steps to Reproduce

1. Open the application.
2. Enter abc in the input field.
3. Click Convert.

Expected Result

The application should display a user-friendly validation message, such as: Please enter a valid number.

Actual Result

Not yet verified. Check whether the application displays an error message or raises an exception.

⸻

Test Environment

* Operating System: Windows (version to confirm)
* Python Version: 3.11 (to confirm)
* GUI Framework: Tkinter

Reported by: Wissam Maroun
Project: Distance Converter — QA & Testing
