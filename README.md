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

## Usage
#### 1. run the batch file: ####
   `main.bat`  
#### 2. When prompted, enter the **target IP address**.  ####
#### 3. Enter the **target username**.  ####
#### 4. Enter the **wordlist filename (including extension)** you downloaded, e.g. `wordlist.txt`. ####

