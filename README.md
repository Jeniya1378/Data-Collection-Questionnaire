# Fatigue & Stress Questionnaire Web App

This is a lightweight, browser-based data collection tool designed for
research studies.\
It runs on **any device** (laptop, iPad, mobile) using a modern web
browser and **requires no installation** or backend server.

The webpage collects the following subjective measures:

-   **Borg CR10** -- Perceived exertion\
-   **STAI-6** -- State anxiety short form *(item texts must be filled
    in by the researcher)*\
-   **VAS (0--100)** -- Visual analog scale (stress, fatigue, or
    customizable label)

All responses are stored **locally** in the browser and exported as a
**downloadable CSV file** after submission.

## 📁 Files

-   **index.html** -- Main questionnaire interface

## 🚀 How to Use

1.  Open **index.html** in any browser:

    -   Chrome
    -   Safari
    -   Firefox
    -   Mobile/iPad browsers

2.  Fill out the participant details and scales.

3.  Click **Submit Response**.

4.  A summary will appear showing:

    -   JSON output
    -   CSV-formatted output
    -   A **Download CSV** button

5.  Save the file (e.g., `survey_response.csv`) for your dataset.

## 🔧 Customization

### 1. Replace STAI-6 placeholder text

Replace with the official item wordings from your licensed source.

### 2. Change VAS label

Modify the default VAS label in the HTML form.

### 3. Add more scales

Duplicate any section to add additional items or multiple timepoints.

## 🌐 Hosting on GitHub Pages

1.  Push the repository to GitHub.
2.  Go to **Settings → Pages**
3.  Select:
    -   Branch: `main`
    -   Folder: `/` (root)

GitHub will generate a public link like:

    https://your-username.github.io/your-repo/

Open the link in any browser to use the questionnaire.

## 📦 No Dependencies Required

-   Pure **HTML + CSS + JavaScript**
-   No frameworks
-   No backend
-   Works offline if opened locally

## 📝 License

This tool is free to use for research and educational purposes.\
Ensure proper licensing for copyrighted questionnaires (e.g., STAI-6).
