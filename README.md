# aust-cover-page-generator
# 📄 AUST Cover Page Generator

A fast, fully automated, and perfectly formatted cover page generator designed specifically for students at Ahsanullah University of Science and Technology (AUST). 

Whether you are submitting a standard **Lab Report**, an **Open Ended Lab (OEL)**, or a **Theory Assignment** (Single or Group), this tool instantly adapts the layout and formatting to match official guidelines. It runs entirely in your browser, requires no internet connection after the initial load, and features a massive built-in database of the EEE department curriculum.

**Created by:** Adittya Sinha Arko

**[Try the Live Demo Here](https://ibuk-i.github.io/aust-cover-page-generator/)**  

---

## Key Features

* **Multi-Format Support:** Instantly switch between Lab Reports, Open Ended Labs, and Assignments. The tool automatically changes labels (e.g., "Experiment Name" becomes "Title") and adjusts the layout.
* **Dynamic Group Tables:** Automatically transforms the "Submitted by" section into a clean, professional multi-member table for group assignments and OELs (supports up to 7 members).
* **📐 Custom Layout Sliders:** Includes real-time sliders to manually adjust the top spacing and left/right positioning of the "Submitted by" section, ensuring perfect alignment no matter how long your title is.
* **Massive Course Database:** Automatically fills in Course Codes, Course Names, and exact Experiment Titles from official lab manuals for EEE courses (1st to 4th Year).
* **Smart File Naming:** Automatically names your downloaded PDF based on your submission type (e.g., `EEE 2105- Assignment- 00724105131.pdf` or `EEE 2200- OEL- Group 06.pdf`).
* **100% Private & Serverless:** No backends or databases. All code runs locally in your browser. Your IDs and data are never tracked or saved.

---

## How to Use It

The generator features a clean, dark-mode sidebar. Everything you change on the left instantly updates the live, printable A4 preview on the right.

### 0. Submission Type & Layout Adjustments
* **Type:** Choose between Lab Report (Single), Open Ended Lab (Group), Assignment (Single), or Assignment (Group). 
* **Sliders:** If you are doing a single submission, use the Top Spacing and Left Position sliders to drag the "Submitted by" block to the perfect spot on the page.

### 1. Department
* **EEE (Default):** Keeps the automated preset system turned on.
* **Other Department:** Grays out the EEE presets and unlocks a blank text box so students from CE, ME, CSE, etc., can type their own department name.

### 2. Automated Presets
* **Course Preset:** Select your Year/Semester and Course.
* **Experiment No:** Automatically populates a list of all official experiments from that specific course's lab manual.
* ** Shift / Override Title:** If teacher skips an experiment or changes the order, use this warning-colored dropdown to swap the title without messing up your manual numbering.

### 3. Final Print Values (Editable)
If a course isn't in the database or you have a custom assignment topic, type directly into these text boxes (**Course Code, Course Name, Exp No, Exp Name**). What you type here is exactly what gets printed.

### 4. Student Identity & Term
* **Single vs. Group:** Depending on your Submission Type, this section will either ask for your individual Name/ID or provide up to 7 rows for group members.
* **Group Checkbox:** You can toggle whether the "Group No" line actually prints on the page.

### 5. Dates (Toggleable)
Use the pop-up calendars to select your Performance and Submission dates. 
* **Show/Hide:** If your assignment doesn't require a Performance Date or Submission Date, simply uncheck the "Show" boxes to remove those lines from the page completely.

---

## Printing & Saving as PDF

When you are ready, click the big green **"Save as PDF / Print"** button at the bottom of the sidebar. From PC, set your destination to "Save as PDF" and save the pdf. For mobile, touch the 3 dot in the upper right section> select "Save as PDF" and your pdf is saved according to your allocated path.

### CRITICAL PRINT SETTING:
When your browser's print menu pops up, you **MUST** click on "More Settings" and check the box that says **"Background graphics"**. If you do not check this box, the browser will strip the green colors out of the AUST logo to save printer ink!

---

## How to Run Locally

If you want to run this on your own machine without using the live link:
1. Clone or download this repository.
2. Ensure both `index.html` and `aust_logo.svg` are in the same folder.
3. Simply double-click `index.html` to open it in any modern web browser (Chrome, Edge, Firefox, Brave, Safari).
##  Contributing

If you notice a missing course or an updated lab manual, feel free to fork the repo, add the new course to the `courseDatabase` object inside the `index.html` file, and submit a Pull Request.
