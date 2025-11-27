---

# Shai-hulud 2.0 — Threat Intelligence Package Scanner

Shai-hulud 2.0 is a lightweight, intelligence-driven scanner designed to detect compromised Python packages within any project directory.
It retrieves live data from five threat-intelligence sources and identifies malicious versions, suspicious packages, and recommended fixes.

---

## Installation & Setup

### 1. Download the ZIP

Download the latest release from the repository:

[https://github.com/ccievks/Ccievks-Threatintel-Repo/tree/main/Shai-hulud-2.0](https://github.com/ccievks/Ccievks-Threatintel-Repo/tree/main/Shai-hulud-2.0)

---

### 2. Extract the Package

Unzip the downloaded archive into any working directory.

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Scanner

To scan a project, point the detector at the project’s root directory:

```bash
python shai_hulud_detector.py --path /your/project/root
```

Example:

```bash
python shai_hulud_detector.py --path ./my_application
```

---

## Understanding the Results

After scanning, you will receive:

### • Compromised Packages

Packages the threat-intel feeds identify as malicious or involved in known attacks.

### • Detected Packages

Packages found in your project or environment during analysis.

### • Malicious Version Ranges

Specific version numbers or ranges that are known to be compromised.

### • Recommended Remediation

Actions such as:

* Updating to safe versions
* Removing malicious dependencies
* Reviewing your dependency chain
* Validating your environment or CI pipeline

These findings help you quickly determine if your software or CI/CD pipeline is at risk.

---
