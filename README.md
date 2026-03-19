# Open Source Audit – Python

## 📌 Student Details
- **Name:** Yash Priyam  
- **Roll Number:** 24BCE10474  
- **Course:** Open Source Software (OSS NGMC)  
- **Chosen Software:** Python  

---

## 📌 Project Overview
This repository contains my capstone project for the OSS course.  
The project is an audit of Python as an open-source software, covering its origin, license, philosophy, ecosystem, and comparison with proprietary alternatives.  

Alongside the written report, I have created **five shell scripts** that demonstrate practical Linux skills and connect to the open-source philosophy of transparency and automation.

---

 ## 📌 Repository Contents
   ```
 oss-audit-24BCE10474/
  ├── README.md
  ├── script1_system_identity.sh
  ├── script2_package_inspector.sh
  ├── script3_disk_auditor.sh
  ├── script4_log_analyzer.sh
  ├── script5_manifesto_generator.sh
  └── screenshots/
  ```
---

## 📌 Scripts

### 1. System Identity Report
- **File:** `script1_system_identity.sh`  
- **Purpose:** Displays Linux distribution, kernel version, user info, uptime, date/time, and license message.  
- **Run:**  
  ```bash
  bash script1_system_identity.sh
  
### 2. FOSS Package Inspector

- **File:** `script2_package_inspector.sh`
- **Purpose:** Checks if Python is installed, prints version info, and shows a philosophy note using a case statement.
- **Run:**
  ```bash
  bash script2_package_inspector.sh

### 3. Disk and Permission Auditor

-   **File:** `script3_disk_auditor.sh`
-   **Purpose:** Loops through key system directories, reports size and permissions, and checks Python config directory.
-   **Run:**
    ```bash
    bash script3_disk_auditor.sh
    
### 4. Log File Analyzer

-   **File:** `script4_log_analyzer.sh`
-   **Purpose:** Reads a log file line by line, counts keyword matches (default: “error”), and prints last 5 occurrences.
-   **Run:**
    ```bash
    bash script4_log_analyzer.sh /var/log/syslog error

### 5. Open Source Manifesto Generator

-   **File:** `script5_manifesto_generator.sh`
-   **Purpose:** Asks the user three questions interactively, generates a personalized open-source manifesto, and saves it to a `.txt` file.
- 
   **Run:**
    ```bash
    bash script5_manifesto_generator.sh


## 📌 How to Use

- Clone the repository:  
  ```bash
  git clone https://github.com/Raunak-24/oss-audit-24BCE10474.git
  cd oss-audit-24BCE10474
-  Make scripts executable:
   ```bash
   chmod +x script*.sh


## 📌 Dependencies


-   Linux system (tested on Ubuntu/Debian)
-   Bash shell
-   Standard utilities: `ls`, `du`, `grep`, `awk`, `dpkg`

