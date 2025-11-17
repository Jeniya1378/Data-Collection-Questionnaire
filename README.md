# Fatigue & Stress Questionnaire Web App

A lightweight, browser-based data-collection tool designed for research studies involving **fatigue**, **stress**, and **perceived exertion**.

The app runs on **any device** (laptop, phone, tablet) using a modern web browser.  
There is **no installation**, **no backend server**, and **no external dependency**.

👉 **Live Web App:**  
https://jeniya1378.github.io/Data-Collection-Questionnaire/

---

## 📋 Included Measures

The questionnaire currently collects:

- **Borg CR10** — Perceived exertion  
- **PSS / STAI-6 (Short Form State Anxiety)**  
  *(Item texts must be inserted by the researcher if copyrighted)*  
- **VAS (0–100)** — Visual analog scale for fatigue, stress, or any customized label

All responses are stored **locally inside the browser** and exported as a **downloadable CSV file** upon submission.

---

## 📁 Files

- **index.html** — Main questionnaire interface (HTML + CSS + JavaScript)

---

## 🚀 How to Use

1. Open **index.html** locally  
   *(or access the hosted version at the link above)*  
2. Enter participant details  
3. Complete the subjective scales  
4. Click **Submit Response**  
5. View the generated:
   - JSON output  
   - CSV-formatted output  
   - **Download CSV** button  
6. Save the CSV file (example: `survey_response.csv`) to include in your dataset.

---

## 🔧 Customization Guide

### 1. Modify STAI-6 / PSS Items
Replace placeholder text in the HTML section with the **official item wording** from your licensed source.

### 2. Change the VAS Label
Locate the VAS section in the HTML and adjust the displayed text (e.g., "Stress Level", "Mental Fatigue", "Effort", etc.).

### 3. Add More Scales or Items
Duplicate existing HTML blocks to create new measurement sections or additional timepoints.

### 4. Adjust Export Structure
Modify the JavaScript object that compiles responses into JSON/CSV if you want:
- multiple trials per participant  
- repeated measures  
- automatic timestamping  
- session identifiers  

---

## 🌐 Hosting Instructions (Already Set Up)

Your site is hosted via GitHub Pages.

To re-deploy or update:

1. Push changes to your GitHub repository  
2. Visit **Settings → Pages**  
3. Ensure configuration is:
   - Branch: `main`  
   - Folder: `/` (root)

GitHub will auto-publish updates at:

**https://jeniya1378.github.io/Data-Collection-Questionnaire/**

---

## 📦 Technical Details

- 100% **HTML + CSS + JavaScript**
- No frameworks required  
- No backend or databases  
- Works offline (if the file is opened locally)  
- Fully portable and easy to customize  

---

## 📝 License

This tool is freely available for **research and educational** use.  
Please ensure you hold the appropriate rights for proprietary questionnaires (e.g., STAI-6 official wording).
