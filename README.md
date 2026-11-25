# NETWORKWALKS-GAURANGB084-WK3-Password-Cracking
# 🔐 PDF Password Recovery Using Networkwalks Online Tools

**W3-PM2 | Cybersecurity & Ethical Hacking | Networkwalks**

---

## 📋 Report Details

| Field | Details |
|---|---|
| 👤 Pentester | Gaurang |
| 🎓 Program / Batch | Cybersecurity & Ethical Hacking Internship |
| 📦 Batch | B084 – Networkwalks |
| 📚 Module | W3-PM2 |
| 🎯 Target | Password-protected PDF provided for the exercise |
| 💻 Platform | Kali Linux |
| ✅ Permission | Authorized internship exercise |

---

## ⚠️ Disclaimer

All activities documented in this practical were performed using the sample PDF provided for the internship exercise, with permission granted by Networkwalks.

This practical is intended strictly for educational and cybersecurity research purposes. Password recovery techniques must only be performed on files that you own or have explicit authorization to test.

---

## 🔭 1. Overview

This module focused on understanding PDF password protection and recovering passwords using Networkwalks online tools.

The practical involved:

1. Locating the password-protected PDF file in Kali Linux.
2. Generating a PDF hash using the Networkwalks Hash Calculator.
3. Copying the generated hash.
4. Submitting the hash to the Networkwalks Password Cracker.
5. Recovering the PDF password.
6. Verifying the recovered password by opening the original PDF.

### Practical Workflow

| Phase | Description | Status |
|---|---|---|
| 1 | Locate the internship sample PDF | ✅ Completed |
| 2 | Generate PDF hash | ✅ Completed |
| 3 | Copy the generated hash | ✅ Completed |
| 4 | Submit hash to Password Cracker | ✅ Completed |
| 5 | Recover PDF password | ✅ Completed |
| 6 | Verify recovered password | ✅ Completed |

---

## 🧰 2. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating system used for the practical |
| Mozilla Firefox | Accessing Networkwalks online tools |
| My Locked PDF1.pdf | Password-protected internship sample |
| Networkwalks Hash Calculator | Generating the PDF hash |
| Networkwalks Password Cracker | Attempting password recovery |
| Oracle VirtualBox | Running the Kali Linux virtual environment |

---

## 🔑 3. Locating the Target PDF

**Target File:** `My Locked PDF1.pdf`

The first step was to locate the password-protected sample PDF provided for the internship exercise.

The file was available in the Downloads directory of Kali Linux.

### Command Used

```bash
cd ~/Downloads
ls -l "My Locked PDF1.pdf"
```

The command verified that the sample PDF was present and accessible.

**Result:** Successfully located the internship sample PDF.

---

## 🧮 4. Generating the PDF Hash

The Networkwalks Hash Calculator was opened using Mozilla Firefox in Kali Linux.

The password-protected PDF was uploaded to the online tool for hash generation.

After processing the file, the tool generated a PDF hash beginning with:

```text
$pdf$
```

This hash contains information required by compatible password recovery tools to attempt password recovery.

**Tool Used:** Networkwalks Hash Calculator

**Result:** Successfully generated the PDF hash.

---

## 📋 5. Copying the Generated Hash

After the hash was generated successfully, the complete hash was selected and copied.

It was important to copy the entire hash without missing any characters because incomplete hash information could prevent the password recovery tool from processing it correctly.

**Result:** Successfully copied the generated PDF hash.

---

## 🔓 6. Password Recovery Using Networkwalks Password Cracker

The Networkwalks Password Cracker was opened in Mozilla Firefox.

The previously generated PDF hash was entered into the tool, and the password recovery process was started.

The tool processed the submitted hash and attempted to identify the password associated with the protected PDF.

**Tool Used:** Networkwalks Password Cracker

### Screenshot

![Password Recovery Process](screenshots/Screenshot_2026-11-23_23_50_34.png)

**Result:** Password recovery process completed successfully.

---

## 🔐 7. Password Recovered Successfully

After the recovery process completed, the tool displayed the recovered password.

The recovered password was used in the next stage to verify whether the original PDF could be unlocked.

| Activity | Status |
|---|---|
| PDF hash generated | ✅ Successful |
| Hash submitted | ✅ Successful |
| Password recovery | ✅ Successful |
| Password verification | ✅ Successful |

### Screenshot

![Recovered Password](screenshots/Screenshot_2026-11-23_23_54_14.png)

---

## 📄 8. Verifying the Recovered Password

The original `My Locked PDF1.pdf` file was opened again.

The recovered password was entered into the PDF password prompt.

The document opened successfully, confirming that the recovered password was correct.

**Final Result:** Successfully unlocked the password-protected internship PDF.

---

## 🚦 9. Risk Analysis

| No. | Finding | Evidence | Potential Impact | Risk |
|---|---|---|---|---|
| 1 | Weak PDF password | Password recovery was successful | Weak passwords may be recovered through guessing attacks | 🟡 Medium |
| 2 | Password hash exposure | PDF hash generated and copied | Exposed hashes can be used for offline password attacks | 🟡 Medium |
| 3 | Reliance on common passwords | Password recovery completed successfully | Common passwords are easier to guess or recover | 🔴 High |
| 4 | Third-party processing | PDF uploaded to an online tool | Confidential documents may be exposed if uploaded without authorization | 🔴 High |

**Note:** PDF password protection depends on the encryption configuration and password strength. Weak passwords can make protected documents vulnerable to password recovery attacks.

---

## ✅ 10. Recommendations

The following security recommendations can help improve PDF document protection:

- 🔐 Use long, strong, and unique passwords for protected PDF documents.
- 🚫 Avoid common passwords and easily guessable combinations.
- 🔑 Use a password manager to generate and store secure passwords.
- 🛡️ Use modern PDF encryption standards, such as AES-256, where supported.
- 🔒 Never upload confidential or personal documents to unknown online password recovery services.
- 🔁 Avoid reusing the same password across multiple documents.
- 🧪 Periodically review the security of password-protected documents.

---

## 🎓 11. What I Learned

Through this practical, I learned:

1. How password-protected PDF documents work.
2. How to generate a PDF hash using an online Hash Calculator.
3. The purpose of PDF hashes in password recovery.
4. How to use Networkwalks Password Cracker.
5. How password recovery tools process extracted hash information.
6. How to verify a recovered password by opening the original document.
7. The importance of strong passwords and secure document handling.

---

## 🏁 12. Conclusion

This practical provided hands-on experience with PDF password recovery using Networkwalks online tools.

I successfully located the internship sample PDF, generated its hash using the Networkwalks Hash Calculator, submitted the hash to the Password Cracker, and recovered the password.

The recovered password was then used to open the original PDF successfully.

This exercise improved my understanding of PDF password protection, hash generation, password recovery techniques, and the importance of strong password security.

It also highlighted the importance of performing password recovery activities responsibly and only with proper authorization.

---

## 👤 Author

**Gaurang**

Cybersecurity & Ethical Hacking Internship  
**Networkwalks | Batch B084**

⭐ *This practical was completed as part of Week 3 cybersecurity and ethical hacking training.*
