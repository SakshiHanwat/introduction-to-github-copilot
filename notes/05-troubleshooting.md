# Troubleshooting Common Training Issues in Microsoft Learn 🛠️

Microsoft Learn is continuously improving its training experience.  
However, users may occasionally face issues while accessing modules, Cloud Shell, or account-related features.

This document lists common issues and their recommended quick fixes to help get unblocked quickly.

---

## Common Issues and Quick Fixes

### 🔐 Account & Sign-in Issues

#### ❗ "MSA account requires additional verification steps."
**Cause:**  
Your Microsoft account hasn’t been used for a while or requires email/phone verification.

**Solution:**  
- Complete account verification through Microsoft Support
- Resolve sign-in issues before accessing Microsoft Learn

---

#### ❗ "Invitation redemption failed."
**Solution:**  
- Navigate back to the unit page  
- Accept the invitation again

---

#### ❗ You can't register your account
**Steps to Fix:**
1. Open your browser in **InPrivate / Private mode**
2. Try registering again
3. Open browser **Console (F12)**
4. Retry registration
5. If it fails, take a screenshot of the console error

---

### ☁️ Azure Cloud Shell Issues

#### ❗ Unable to start the Cloud Shell
**Cause:**  
Third-party cookies are blocked.

**Fix by Browser:**
- **Edge:** Settings → Privacy & Security → Cookies → Don’t block cookies  
- **Internet Explorer:** Internet Options → Privacy → Advanced → Accept third-party cookies  
- **Firefox:** Tools → Options → Privacy → Accept third-party cookies  
- **Chrome:** Settings → Privacy & security → Cookies → Turn off “Block third-party cookies”

---

#### ❗ "You're signed into the Cloud Shell with a different account"
**Solution:**
- Select **Sign out** below the error
- Clear browser cache/cookies
- Try signing in using an **incognito window**

---

#### ❗ "Cloud Shell exceeds the active user quota."
**Solution:**
- Refresh the page
- Wait **20 minutes** and try again

---

#### ❗ "AuthorizationFailed" / "resource group not found"
**Solution:**
- Open a **private browser window**
- Sign in again
- Clear browser cache if needed

---

#### ❗ "Storage creation failed."
**Solution:**
- Clear browser cache/cookies
- Retry in an incognito/private window

---

#### ❗ Azure Cloud Shell opens without a prompt
**Known Issue:**  
Occurs in **Microsoft Edge** and **Safari**

**Fix:**  
- Use **Google Chrome** for best experience

---

#### ❗ "Failed to connect to MSI. Please make sure MSI is configured correctly."
**Fix:**
1. Open Azure Cloud Shell from the module page
2. Run:
   ```bash
   az login
    ```

3. Follow the steps mentioned in the module

---

### 📊 Progress & Badge Issues
❗ Progress isn’t saving

Reason:
Progress may take a few seconds to update.

Fix:

Wait a few seconds

Refresh the page

❗ Completing a module doesn’t grant a badge/trophy

Cause:
Common in Internet Explorer

Fix:

Open Microsoft Learn profile in a different browser (Chrome/Edge)

---

## 📁 File & Command Errors
❗ "No such file or directory"

Solution:

Verify your current directory

Confirm the folder structure before running commands

---

### 🔗 Account Linking Issues
Linking a personal or work account

Steps:

Sign in to your existing Microsoft Learn profile

Go to Profile

Open Settings

Under Account Management, select Add account

Sign in with the account you want to link

⚠️ If you see:

"You're about to merge these two profiles"

It means both accounts already have profiles.
You can merge them into one.

---

📌 Note:

One profile can have 1 personal account

Up to 5 work or school accounts

---

### 🏆 Cloud Skills Challenge Issues
❗ Issues with a Cloud Skills Challenge

Fix:

Email the support address mentioned on the challenge page

Include:

Challenge URL

Microsoft Learn profile username

⚠️ If prizes are involved, refer to the official challenge rules

---

### ✅ Key Takeaway

- Most Microsoft Learn issues are related to:

- Account verification

- Browser settings

- Cache or cookie conflicts

- Cloud Shell availability

Using a modern browser (Chrome), private mode, and proper sign-in usually resolves most problems quickly.


---

