# 🐞 Bug Report: Registration Form – Email Field Accepts Invalid Format

## 🔎 Summary
The registration form allows submission with an invalid email format (`testemail.com` – missing `@`). This results in either unexpected behavior or incorrect user account creation.

## 📍 Steps to Reproduce
1. Go to the [PrestaShop demo registration page](https://dev-mystore-testlab.coderslab.pl/index.php?controller=authentication&create_account=1).
2. In the "Email" field, enter: `testemail.com`
3. Fill out the rest of the required fields correctly.
4. Click the **"Register"** button.

## ✅ Expected Result
The system should display an error message like: `"Please enter a valid email address."` and prevent form submission.

## ❌ Actual Result
The form accepts the input and continues the registration process.

## 💻 Environment
- **OS:** Windows 10
- **Browser:** Google Chrome 123
- **Test Type:** Functional Manual Test
- **Priority:** High
- **Severity:** Major

---

### 📂 File name suggestion:
`BugReport_RegistrationEmail.md`
