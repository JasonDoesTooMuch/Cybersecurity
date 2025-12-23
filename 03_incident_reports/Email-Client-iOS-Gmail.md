**Incident Report : Email Synchronization Failure (iOS Mail & Android Tablet**

--- 

**Summary**

Assisted a user with setting up a new android tablet to access Gmail, which resulted in an email synchronization issue on the user's iPhone. The iPhone was no longer able to send or receive emails through the native mail application, while email delivery continued on the tablet. The issue was diagnosed, resolved, and fully documented 

---

**Environment**
- **Tablet :** Samsung Galaxy A8 (Android)
- **Phone :** iPhone (iOS)
- **Email Provider :** Gmail
- **Email Clients :** Gmail app, iOS Mail app

---

**Initial Request**
The user requested assistance setting up a new tablet to access their email. During setup, the user was unable to recall their email password and required a password reset before proceeding 

---

**Actions Taken**

**Password Reset & User Education**
* Initiated Gmail password reset using an already authenticated device
* Verified reset email was successfully received
* Completed password reset process
* Educated the user on :
  - The importance of periodic password updates
  - Secure password storage to prevent future access issues
* Advised the user to securely record the new password

---

**Problem Identification**

Following tablet setup : 
- The user stopped receiving emails on their iPhone
- Emails were only arriving on the tablet
- Attempts to send or receive emails through the iOS Mail app failed
- SMTP errors prevented outgoing and incomng mail on the iPhone

---

**Troubleshooting Process**

1. Attempted test email from the iPhone mail app (failed)
2. Verified the Gmail account was still present in iOS Mail settings
3. Confirmed SMTP connection errors persisted
4. Identified potential account desynchronization between devices
5. Conducted research on Gmail and iOS Mail synchronization behavior
6. Removed the Gmail account from the tablet
7. Restarted the tablet
8. Removed Gmail account from iPhone settings
   * Settings --> Apps --> Mail --> Accounts
10. Restarted the iPhone

---

**Outcome**

- Email functionality fully restored on the iPhone
- Tablet email access maintained
- No data loss occurred
- User successfully educated on password management and setup awareness

---

**Root Cause**

Account desynchronization caused by skipped email integration settings during initial tablet setup, resulting in SMTP authentication failures within the iOS Mail app

---

      **Continuation**

