Test Cases — Distance Converter

Functional Test Cases

Test ID	Test Scenario	Test Data	Expected Result	Status
TC-01	KM to Miles conversion	10	Approximately 6.21 miles	To Verify
TC-02	Decimal input	5.5	Correct converted value	To Verify
TC-03	Zero input	0	Display 0	To Verify
TC-04	Negative input	-5	Validate according to requirements	To Verify
TC-05	Empty input	Empty	Display a validation message	To Verify
TC-06	Non-numeric input	abc	Display an error message without crashing	To Verify
TC-07	Large number	999999	Handle the value without an unexpected error	To Verify
TC-08	Special characters	@#$	Display a validation message	To Verify

Testing Types

* Positive Testing
* Negative Testing
* Boundary and Edge-Case Testing
* Manual Functional Testing

Notes

Test results will be updated after each test is executed. Confirmed defects will be documented in BUG_REPORT.md.

Tester

Wissam Maroun

Project: Distance Converter — QA & Testing
