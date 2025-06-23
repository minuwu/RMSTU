# 📘 RMSTU Repository Contribution Guide

Welcome!
This guide will help you contribute to the `RMSTU` academic resource repository by following the proper structure and naming conventions.

---

## 🧾 Overview

The `RMSTU` repo is organized by:

* **Department** (e.g., `CSE`, `MGT`, `THM`)
* **Year–Semester** folders (e.g., `1-1`, `2-2`)
* **Batch** folders (e.g., `6th batch`, `7th batch`)
* **Files** for each exam phase and result (e.g., `1-1_mid1Ques.pdf`, `1-1_FinalQues.pdf`, `1-1_Result.pdf`)
* **README.md** mapping of course names and respective course teachers.

<details>
<summary>more</summary>
This structure helps juniors identify faculty-specific question patterns and academic trends.
</details> 




### ✅ You must:

* Follow the **same folder structure**
* Name files in the exact format shown
* Use appropriate **department**, **semester**, and **batch**
* Upload only PDF files

---

## 🗂 Folder Structure

```
RMSTU/
├── CSE/
│   ├── 1-1/
│   │   ├── 6th batch/
│   │   │   ├── 1-1_mid1Ques.pdf
│   │   │   ├── 1-1_mid2Ques.pdf
│   │   │   ├── 1-1_FinalQues.pdf
│   │   │   ├── 1-1_Result.pdf
│   │   │   └── README.md   ← course-teacher mapping here
│   ├── 1-2/
│   │   └── 6th batch/
├── MGT/
│   └── 1-1/
│       └── 7th batch/
└── THM/
    └── 2-2/
        └── 8th batch/
```

---

## 📌 File Naming Rules

Each file inside a `batch` folder must follow the format:

* `YY-SS_mid1Ques.pdf` — for Mid 1 questions
* `YY-SS_mid2Ques.pdf` — for Mid 2 questions
* `YY-SS_FinalQues.pdf` — for Final Exam questions
* `YY-SS_Result.pdf` — for results

✅ Also Required:
A README.md file listing courses and course teachers. This helps others understand question patterns.

> Example for 1st year 1st semester of 6th batch in CSE:
> `1-1_mid1Ques.pdf`, `1-1_Result.pdf`

---

## 👣 How to Contribute

1. **Fork** the repository
2. **Clone** your fork to your device
3. Add your files under the correct folder path:

   ```
   [Department]/[Year-Semester]/[Batch]/[Files]
   ```
4. Double-check:

   * 🏷 Correct department (CSE/MGT/THM)
   * 📁 Folder names match the format
   * 📄 File names are correct and are in **PDF format**
5. **Commit and Push** your changes
6. Open a **Pull Request**

---

## ❗ Important Notes

* **Do NOT** rename existing folders or files
* **Do NOT** add duplicate content or alternate formats
* If your department doesn’t exist yet, create it at the root level (same as `CSE/`)
* You can only contribute to your own batch. Create a new batch folder if needed (`7th batch`, `8th batch`, etc.)

---

## 🙋 Need Help?

Open an issue or discussion on the GitHub repo if you:

* Are unsure where your files go
* Need a new department or semester added
* Want help with Git commands or file formatting

---

Ready to contribute? Let’s build this archive together! ✨
