# 🔍 Defect Analysis  

---

## I. Inconsistencies (5)

### 1. Conflict Between Deadline Rules (R2, R3)  
R2 states registration is not allowed after the deadline, while R3 allows late registration for 3 days after the deadline. This creates a logical contradiction.

### 2. Seat Availability Conflict (R5, R16)  
R5 allows registration even if seats are full, while R16 introduces waitlisting when seats are full. Both rules conflict.

### 3. Schedule Conflict Exception (R9, R10)  
R9 prevents schedule conflicts, but R10 allows same-time registration if one course is online. The exception is not clearly defined.

### 4. Credit Hour Limit Conflict (R11, R12)  
R11 limits students to 18 credit hours, while R12 allows up to 24 credit hours with advisor approval. Two different maximum limits create inconsistency.

### 5. Course Drop Deadline Conflict (R13, R15)  
R13 allows dropping until Week 6, while R15 states no drops after the deadline. The deadline is not clearly defined.

---

## II. Incompleteness (5)

### 6. Confirmation Method Missing (R6)  
The requirement does not specify whether confirmation is sent via email, SMS, or system notification.

### 7. Instructor Approval Process Undefined (R8)  
No workflow is defined for how instructor approval is granted or recorded.

### 8. Drop Fee Amount Not Specified (R14)  
The fee amount or calculation method is not defined.

### 9. Registration Deadline Not Defined (R2)  
The exact date and time of the registration deadline are not specified.

### 10. Priority Enrollment Criteria Undefined (R19)  
The requirement does not define how priority enrollment is implemented.

---

## III. Ambiguities (3)

### 11. “Register for Courses” (R1)  
The scope and conditions of registration are not clearly defined.

### 12. “Send Confirmation” (R6)  
It is unclear whether confirmation applies to registration, dropping, or waitlisting.

### 13. “Priority Enrollment” (R19)  
The meaning of priority is not clearly defined (priority in processing order or early access?).

---

## IV. Unverifiable / Untestable Requirements (2)

### 14. “Register Quickly” (R20)  
The word “quickly” is subjective and not measurable.

### 15. “Show Available Seats” (R4)  
The requirement does not define real-time accuracy or refresh timing, making it difficult to test.

---

## 📊 Summary

The requirement set contains:

- Logical conflicts  
- Missing business rules  
- Undefined processes  
- Non-measurable statements  

These defects may lead to incorrect implementation, system failures, and testing difficulties. Requirements should be refined before development begins.
