# ✅ Manual Test Cases – Instagram (Web)

This repository contains sample manual test cases for core Instagram web functionalities. These can be useful for QA interviews, practice, or freelance projects.

---

## 📋 Module: Login Functionality

| TC ID | Test Case Description | Steps to Execute | Expected Result | Priority | Status |
|-------|------------------------|------------------|------------------|----------|--------|
| TC01  | Verify login with valid credentials | 1. Go to login page<br>2. Enter valid username and password<br>3. Click "Log in" | User is successfully logged in and redirected to the feed | High | Not Executed |
| TC02  | Verify login with invalid credentials | 1. Enter wrong username/password<br>2. Click "Log in" | Error message is displayed | High | Not Executed |
| TC03  | Verify login with blank username | Leave username field empty and try logging in | Error message: "Username required" | Medium | Not Executed |
| TC04  | Verify password field is masked | Check the password field on input | Password should be shown as bullets/dots | Low | Not Executed |

---

## 📋 Module: Post a Photo

| TC ID | Test Case Description | Steps to Execute | Expected Result | Priority | Status |
|-------|------------------------|------------------|------------------|----------|--------|
| TC05  | Verify successful photo upload | 1. Log in<br>2. Click "New Post"<br>3. Upload valid image<br>4. Click "Share" | Image appears on profile/feed | High | Not Executed |
| TC06  | Verify upload with unsupported format | Try uploading a `.exe` or `.pdf` file | Error message shown: "Unsupported file type" | Medium | Not Executed |
| TC07  | Cancel post before sharing | Start a post and click "Cancel" | User is taken back without posting | Low | Not Executed |

---

## 📋 Module: Logout

| TC ID | Test Case Description | Steps to Execute | Expected Result | Priority | Status |
|-------|------------------------|------------------|------------------|----------|--------|
| TC08  | Verify logout button | Click on profile > "Log out" | User is logged out and taken to login page | High | Not Executed |
| TC09  | Try accessing home after logout | Press back button or use browser history | User should not access feed; redirected to login | Medium | Not Executed |

---

## 📌 Notes
- Status can be updated after execution.
- These test cases assume Instagram's UI is unchanged.
- You can extend this repo with **signup, messaging, profile update**, etc.
