<p align="center">
<img src="Screenshots/banner.png" width="900">
</p>

# 🔍 M57-Jean Digital Forensics Investigation

A complete end-to-end digital forensic investigation of the **M57-Jean** training scenario using **FTK Imager** and **Autopsy**. This case study demonstrates the forensic methodology used to determine how confidential employee information was exfiltrated from a Windows XP system.

---

![Platform](https://img.shields.io/badge/Platform-Windows_XP-blue)
![Tool](https://img.shields.io/badge/Tool-Autopsy-orange)
![Tool](https://img.shields.io/badge/Tool-FTK_Imager-green)
![Case](https://img.shields.io/badge/Case-M57--Jean-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

The objective of this investigation was to determine how a confidential employee spreadsheet left Jean's laptop and evaluate the claim that the system had been compromised by an external attacker.

The investigation followed a structured forensic workflow including evidence verification, artifact analysis, timeline reconstruction, evidence correlation, and professional reporting.

---

## 🖥️ Case Information

| Field | Value |
|-------|-------|
| Case ID | DF-001 |
| Case Name | M57-Jean Insider Data Exfiltration Investigation |
| Operating System | Windows XP |
| Evidence Format | Expert Witness Format (E01) |
| File System | NTFS |

---

## 🛠️ Tools Used

- FTK Imager
- Autopsy
- HxD Hex Editor

---

## 🔬 Investigation Scope

- Evidence Verification
- File System Analysis
- Spreadsheet Analysis
- Browser Artifact Analysis
- Email Forensics
- USB Device Analysis
- Timeline Reconstruction
- Evidence Correlation
- Forensic Reporting

---

## 📂 Repository Structure

```
Documentation/
│
├── Case-Brief.md
├── Case-Diary.md
├── Artifact-Log.md
├── Timeline.md
├── Investigation-Board.md
├── Forensic-Examination-Report.md

Notes/
│
└── Concepts.md

Screenshots/

Exports/

README.md
LICENSE
```

---

## 🎯 Key Findings

- Confidential spreadsheet recovered from the suspect's Desktop.
- Spreadsheet contained employee names, salaries, and Social Security Numbers (SSNs).
- Email analysis identified a request for confidential employee information.
- The suspect replied with an attached Microsoft Excel document.
- The attachment matched the recovered spreadsheet.
- Recipient acknowledged successful receipt of the file.
- No evidence supporting browser-based exfiltration or external compromise was identified.

---

## 💡 Skills Demonstrated

- Evidence Verification
- Windows File System Analysis
- Email Forensics
- Windows Artifact Analysis
- Timeline Reconstruction
- Evidence Correlation
- Digital Forensic Documentation
- Professional Report Writing

---

## 📚 Learning Outcomes

This investigation demonstrates practical application of:

- Digital Forensic Methodology
- Windows Artifact Analysis
- Email Investigations
- Timeline Reconstruction
- Evidence Correlation
- Incident Documentation

---

## ⚠️ Disclaimer

This repository is intended solely for educational and portfolio purposes.

The investigation was conducted using the publicly available **M57-Jean** forensic training dataset.

The findings are based exclusively on the supplied forensic image and do not represent a real criminal investigation.

---

## 📄 License

This project is released under the MIT License.
