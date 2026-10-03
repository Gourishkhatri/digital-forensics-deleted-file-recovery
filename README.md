\# Digital Forensics Lab — Deleted File Recovery



\## Overview



A controlled digital forensics laboratory project demonstrating the identification, analysis, recovery, hashing, and documentation of deleted synthetic files using Autopsy.



\## Case Information



\- Case ID: DFR-001

\- Case Name: Deleted File Recovery Investigation

\- Examiner: Gourish Khatri

\- Tool: Autopsy 4.23.1

\- Evidence Image: DFR-001-E002.E01

\- Environment: Controlled Training Laboratory

\- Timezone: Asia/Calcutta (GMT+5:30)



\## Objective



The objective of this investigation was to analyze a synthetic forensic image and demonstrate the recovery of deleted files using a structured digital forensics workflow.



\## Tools Used



\- Autopsy 4.23.1

\- FTK Imager

\- Windows PowerShell

\- MD5

\- SHA-256



\## Investigation Workflow



1\. Created synthetic digital evidence.

2\. Created a forensic disk image using FTK Imager.

3\. Loaded the E01 forensic image into Autopsy.

4\. Performed forensic ingest analysis.

5\. Examined deleted and unallocated files.

6\. Recovered relevant deleted evidence.

7\. Reviewed recovered content using Autopsy.

8\. Calculated MD5 and SHA-256 hashes.

9\. Tagged recovered evidence.

10\. Generated an HTML forensic report.

11\. Documented the investigation and findings.



\## Recovered Evidence



| Evidence | Recovered File | Size |

|---|---|---:|

| Confidential Investigation Report | `$RJT1E2X.txt` | 683 bytes |

| Authentication Log | `$R7B81OO.txt` | 461 bytes |

| Evidence Image | `$RAZ21YG.jpg` | 50,626 bytes |



\## Authentication Log



The recovered synthetic authentication log contained login, file-access, and logout events associated with the controlled training environment.



Example events included:



\- `09:14:22` — analyst01 — Successful login

\- `09:18:41` — analyst01 — File access

\- `10:05:13` — analyst01 — Successful login

\- `11:32:07` — admin01 — Successful login

\- `14:21:55` — analyst01 — File access

\- `18:47:12` — analyst01 — Logout



\## Hash Verification



MD5 and SHA-256 hashes were calculated for the extracted recovered copies.



Detailed hash values are available in:



`Hashes/DFR-001\_Recovered\_File\_Hashes.txt`



\## Evidence Documentation



Investigation screenshots are available in:



`Screenshots/`



The generated Autopsy HTML report is available in:



`Report/report.html`



Investigation notes are available in:



`Notes/DFR-001\_Investigation\_Notes.txt`



\## Repository Structure



```text

Digital-Forensics-Lab/

├── Evidence/

├── Hashes/

├── Notes/

├── Report/

│   ├── Recovered-Files/

│   └── report.html

├── Screenshots/

└── README.md

