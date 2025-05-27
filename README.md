<<<<<<< HEAD
# 🛡️ Phishing Email Analysis Project

Hi! This is a small project where I analyzed a suspicious email to identify phishing indicators. The goal is to understand how phishing works and what signs to look out for.

---

## 🧪 What This Project Is About

I received (or simulated) a suspicious email that claimed to be from Microsoft. I went through it step-by-step to check for signs that it could be fake or dangerous.

---

## ✅ Steps I Followed

### 1. Check the Sender's Email
- The email came from: `security@microsoftsupport.com`
- That domain looks official but it's not really from Microsoft!
- ⚠️ Microsoft usually sends emails from `@microsoft.com` or similar.

---

### 2. Look at the Email Headers
- I used an **email header analyzer** (like [MxToolbox](https://mxtoolbox.com/EmailHeaders.aspx))
- I looked for SPF and DKIM entries, but:
  - ❌ No SPF = not verified
  - ❌ No DKIM = might be spoofed
- This tells me the email might be **fake**.

---

### 3. Spot Suspicious Links or Attachments
- The email had a button: `Review recent activity`
- But the real link was: `http://secure-microsoft-verify-login.com`
- 🚨 Not a real Microsoft domain!

---

### 4. Urgent or Scary Language
- It said: *"We detected something unusual..."*
- And: *"Secure your account immediately!"*
- 🧠 This is a trick to scare users into clicking.

---

### 5. Hover Over Links
- Always hover over links!
- What it *says* and where it actually *goes* might be different.
- ✅ That's what happened in this case.

---

### 6. Look for Spelling/Grammar Issues
- No obvious typos here, but:
  - No username
  - Very generic message
- That’s suspicious because real services usually personalize emails.

---

## 🚨 Summary of Red Flags

| 🔍 Check                  | ❗ What I Found |
|--------------------------|----------------|
| Fake sender address      | `microsoftsupport.com` |
| No SPF/DKIM auth         | Might be spoofed |
| Suspicious link          | Not official Microsoft |
| Urgent language          | Pressures the user |
| Generic message          | No personalization |

---

## 📁 Files in This Repo

- `suspicious_email_sample.eml` — a sample phishing email (for practice)
- `README.md` — this file!

---

## 🙋‍♂️ Why I Did This

I wanted to learn how to analyze phishing emails. This kind of knowledge is useful for staying safe online — and it's also pretty fun to investigate these scams!

---

## 📚 Resources I Used

- [MxToolbox - Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Google: How to spot phishing](https://support.google.com/mail/answer/8253)
- [Microsoft: Report phishing](https://www.microsoft.com/en-us/security/portal/mmpc/shared/report.aspx)

---

Thanks for checking it out! Stay safe on the internet ✌️

# phishing-email-analysis

