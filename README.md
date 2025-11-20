# LSCMRC Rat Exhibit Entry Form

A simple web form for submitting show entries to the **LSCMRC** (London & Southern Counties Mouse & Rat Club).  
Entries are submitted online and emailed to the show secretary via [EmailJS](https://www.emailjs.com/).

---

## Live Form

GitHub Pages:  
https://espritrats-cloud.github.io/LSCMRC-Entry-Form/

---

## What this form does

- Collects member details (name/stud name, email, phone, membership, junior).
- Optional **tank hire**:
  - Up to 2 hire tanks at £1.50 each.
- **Show Entries – Varieties**:
  - Dynamic sections so exhibitors can add multiple exhibits.
  - Each exhibit records:
    - Rat name  
    - Age (Adult / Kitten)  
    - Sex (Doe / Buck)  
    - Section and Class  
    - Novice status  
    - Optional **Dual Entry (Pets)**.
- **Pets section**:
  - Dynamic pet entries (name, section, sex).
- **Automatic cost calculation**:
  - £1 per exhibit  
  - £1 per pet  
  - +£1 for each **Dual Entry (Pets)** ticked  
  - +£1.50 per hire tank (max 2).

All of this is sent in a formatted email to the show secretary, including a full list of exhibits, pets and the total cost.

---

## Tech stack

- **HTML + CSS + vanilla JavaScript**
- **EmailJS** for sending form data as an email
- Hosted via **GitHub Pages**

---

##  Project structure

## Files

- `index.html` – live show entry form (used by GitHub Pages)
- `test.html` – development/test copy. Changes are tested here first, then copied into `index.html` when confirmed.

---

## How to run locally

1. Clone the repo:
   ```bash
   git clone https://github.com/espritrats-cloud/LSCMRC-Entry-Form.git
   cd LSCMRC-Entry-Form
   
## 🐀 Credits
Built for the **LSCMRC** by Samantha to simplify rat show entries and reduce manual admin work.
