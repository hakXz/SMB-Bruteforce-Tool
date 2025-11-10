# SMB-Bruteforce-Tool

## Safety notice
This project is for **defensive research, training, and isolated lab testing only**. Do **not** run it against systems you do not own or do not have **explicit written permission** to test. Unauthorized password guessing or access is illegal.

## What it does
A minimal proof-of-concept that illustrates automated password-guessing behavior against SMB services. Intended uses: validate account lockouts/throttling, test SIEM/IDS detection, and train blue-team analysts — **only** in a controlled lab.

## Installation
```bash
git clone https://github.com/hakXz/SMB-Bruteforce-Tool.git
``` 
```bash
cd SMB-Bruteforce-Tool
```

## Usage (high-level)
Run the provided `.bat` file **only** inside an isolated lab environment and against test targets you control. The script will prompt for the necessary inputs when run.  
If you are the repository owner or have **explicit written authorization**, confirm that and I will provide the detailed, authorized-only usage steps (what the script prompts for and example safe inputs).
