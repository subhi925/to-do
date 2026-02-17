# QA Cart Todo – Software Test Documentation (STD)

This repository contains the Software Test Documentation (STD) for the QA Cart Todo application:

https://qacart-todo.herokuapp.com/todo

## Scope
The document covers functional testing of the **Signup** feature.

## Test Coverage
- Field validation (First Name, Last Name, Email, Password)
- Boundary value analysis (minimum character length)
- Negative scenarios (empty fields, invalid format)
- Duplicate email validation
- Password format validation
- Password confirmation matching
- Positive end-to-end signup flow

## Testing Type
- Manual Functional Testing
- Positive & Negative Testing
- Boundary Value Analysis (BVA)

## Result
All test cases passed except one boundary case (First Name = 3 characters), which indicates a possible requirement mismatch or validation defect.

---

**Tester:** Subhi Mouhammed Hamed  
**Role:** Software QA  
