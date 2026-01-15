# Wefans Project – Pending Frontend & Backend Work

This document lists the currently pending items identified during the backend handover.  
Some tasks are blocked due to missing database-level mapping and business logic clarity.

---

## 1. Authentication & Security

### Google Authentication + Email OTP
- Google OAuth login integration pending
- Email-based OTP flow pending:
  - OTP generation
  - OTP verification
  - Expiry & resend handling

### Login History Tracking
- Persist user login history in the database
- Track:
  - Page from which the user logged out
  - Login device details (browser, device type, etc.)
  - (Optional) IP address

---

## 2. Dashboard

- Dashboard backend APIs are pending
- Dashboard frontend UI implementation is pending

---

## 3. Section Type Master – Repeater Flag

### Repeater Flag Functionality (flag = "no")
- Business logic for repeater flag is not implemented
- Use-case of repeater flag is not clearly defined
- Effect on database structure and data flow is unclear
- Backend logic and frontend behavior are both pending

---

## 4. Schema Validation

### Backend
- API request/response schema validation missing for multiple endpoints

### Frontend
- Form validation rules not fully aligned with backend schemas

---

## 5. Biography Field

- Biography field requires a rich text editor
- Safe storage and rendering of formatted content required

---

## 6. Database Mapping & Sync Issues



### Other Pending Table / Collection Mappings
- Multiple database table/collection relationships are missing or undocumented
- Foreign key / reference logic is unclear in several areas
- API behavior depends on these mappings, blocking further implementation
- Clarification and documentation of DB relationships are required before proceeding

> **Note:** Several features are currently blocked due to missing or unclear database-level mappings.

---

## 7. Privilege & Access Control

### Privilege Module
- Privilege-related tables/collections and their relationships are incomplete
- Role ↔ privilege mapping logic is pending

### UI Update
- Change privilege section title from **"List"** to **"Publish"**
- Backend and frontend alignment required

---

## Important Notes

- This list includes both frontend and backend responsibilities
- Some items are blocked due to missing database relationships and business logic
- Scope, timelines, and estimates depend on clarification of mappings

---
