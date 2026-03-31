#Team Name
##Bits to bytes
# Project Name
Gemini Security Scanner
## Problem Statement
Manual code reviews are time-consuming and often miss critical security vulnerabilities like hardcoded secrets, injection flaws, and insecure configurations. Developers need an automated, intelligent way to identify and remediate these risks before code reaches production to prevent data breaches and system exploits.

## Project Description
The Gemini Security Scanner is an AI-powered static analysis tool designed to perform deep security scans on source code. It allows users to upload source files (supporting .js, .py, .java, .go, and .php) or entire ZIP archives for analysis. The tool doesn't just find bugs; it categorizes them by severity (Critical, High, Medium), provides a "Security Score" and "Health Index," and generates actionable remediation steps. What sets it apart is the "AI Tool Suggestion" feature, which provides specific code refactoring prompts and logic to fix the identified flaws instantly.

## Google AI Usage
### Tools / Models Used
Gemini 3.1 Pro: The primary LLM engine used for analyzing the codebase, identifying patterns of vulnerability, and generating remediation logic.

### How Google AI Was Used
Gemini 3.1 Pro is integrated as the core analytical engine. It is used to:

Identify Vulnerabilities: Scan the uploaded source.py file to detect secrets (Hardcoded Admin Secret Key), security flaws (SQL Injection, XSS, Command Injection), and code anomalies (Hardcoded Debug Mode).

Deep Analysis: Provide a detailed context for why a specific line of code is a risk.

Remediation & Refactoring: Generate "AI Tool Suggestions" that provide developers with specific code snippets (e.g., using os.environ for secrets or shutil.copy for safe file handling) to fix the vulnerabilities.

## Proof of Google AI Usage
Attach screenshots in a `/proof` folder:

<img width="1302" height="716" alt="Capture" src="https://github.com/user-attachments/assets/49e6c736-2477-408b-aeeb-10f45d2b591d" />
<img width="1260" height="613" alt="Capture1" src="https://github.com/user-attachments/assets/086653c2-2945-4d61-8868-92817b669bee" />


---

## Screenshots 
Add project screenshots:
<img width="1302" height="716" alt="Capture" src="https://github.com/user-attachments/assets/658f0414-c20d-484f-96cb-650b15c63d23" />

<img width="1260" height="613" alt="Capture1" src="https://github.com/user-attachments/assets/9de708d5-a626-4169-ae53-cb34d8cdc826" />


---

## Demo Video

https://drive.google.com/file/d/1p6zGcbsrr0s1UQu9UN72btcdPMAVvM2Z/view?usp=sharing

## Installation Steps

```bash
# Clone the repository
git clone <your-repo-link>

# Go to project folder
cd project-name

# Install dependencies
npm install

# Run the project
npm start
