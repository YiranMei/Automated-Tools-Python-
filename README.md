# Automation Tools: Membership Cleanup & Text Analyzer

## Overview
This repository contains two standalone Python tools designed for everyday automation tasks:

1. **Membership Cleanup Automation Tool**  
   - Automatically removes inactive members from a website/shop membership file.  
   - Preserves headers and formatting.  
   - Moves inactive members to an archive file for record keeping.  

2. **Text Analyzer Tool**  
   - A flexible text analysis utility that can be adapted for different domains.  
   - Extracts word frequencies and key patterns from raw text.  
   - Useful for analyzing customer feedback, HR surveys, compliance reports, social media comments, and more.  

---

## Tools Included

###  1. Membership Cleanup Automation Tool
**Purpose:**  
Automates the process of cleaning up inactive members in membership records (e.g., website or shop loyalty programs).

**Features:**
- Keeps active members in `current_members.txt`.  
- Moves inactive members to `inactive_members.txt`.  
- Preserves headers and file formatting.  
- Supports automation across multiple files (monthly cleanup).  

**How It Works:**
1. Generates sample membership files for testing.  
2. Runs a cleanup function to detect inactive members (`Active == 'no'`).  
3. Writes active members back to the main file and appends inactive members to the archive file.  

---

###  2. Text Analyzer Tool
**Purpose:**  
Performs text analysis on any input string or file to extract key insights.  

**Example Applications:**
- **Customer Feedback Analysis** → Find top issues or praise keywords in reviews.  
- **HR Survey Summaries** → Highlight common concerns in employee feedback.  
- **Meeting/Report Summaries** → Quickly identify repeated themes or terms.  
- **Social Media Comment Analysis** → Detect trending topics or sentiment hints.  
- **Compliance Reports** → Spot recurring audit issues (e.g., KYC, AML, late filing).  

**Features:**
- Cleans and tokenizes text into words.  
- Outputs word frequencies.  
- Easily extendable for advanced NLP tasks (sentiment analysis, topic modeling).  

---

## Installation & Usage

### Prerequisites
- Python 3.7+
- No external dependencies for basic usage (`collections`, `re` used only).

