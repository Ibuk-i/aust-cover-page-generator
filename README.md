# aust-cover-page
# 📄 AUST Lab Report Cover Page Generator

Hey everyone! I got tired of manually typing out, formatting, and aligning cover pages for every single lab report, so I built this quick generator for us AUSTians.

It has a massive built-in database of the EEE curriculum (from 1st year all the way to 4th year). You just pick your course and experiment from a dropdown, type in your ID, and it perfectly formats an A4 cover page ready to print or save as a PDF.

👉 **[Use the Generator Here](https://www.google.com/search?q=https://yourusername.github.io/aust-cover-page/)**

*(Note: Replace the link above with your actual GitHub Pages URL once it's live!)*

---

## ✨ Why use this?

* **No more typing long experiment names:** All the official course codes, names, and experiment titles from the lab manuals are already loaded in.
* **Dark mode for you, Light mode for the printer:** The interface is dark so it doesn't blind you at 2 AM when you're rushing to finish a report, but the actual A4 preview stays white so it prints perfectly.
* **Auto-names your files:** When you save, it automatically names your PDF something neat like `EEE 2200- Exp 01- Cover Page [Auto Generated].pdf` so your folders stay organized.
* **100% Private:** There are no servers involved. Everything runs locally right in your browser, meaning your student ID and name are totally private.
* **Perfect Formatting:** Uses the exact AUST standard fonts (Times New Roman & Calibri) and margins.

---

## 🚀 How to Use It

The sidebar on the left has 5 quick sections. Whatever you type on the left instantly updates the live preview on the right.

**1. Department**
It defaults to Electrical & Electronic Engineering. If you're from CE, ME, CSE, or another department, just select "Other Department" and type yours in.

**2. Automated Presets (The Magic Part)**
Pick your Year/Semester and select your Course. The "Experiment No" dropdown will automatically update with all the official experiments for that lab.
*Tip: If the sir skips an experiment or changes the order (e.g., you are doing Exp 4 but it's officially listed as Exp 3), use the warning-colored "Shift / Override Title" dropdown to fix it without messing up your numbering!*

**3. Final Print Values (Editable)**
If your course isn't in the database yet, or if you were given a completely custom experiment name, just type directly into these text boxes. Whatever you type here is exactly what gets printed on the page.

**4. Student Identity**
Drop in your Name, ID, Section (e.g., A2), and Group.

**5. Dates**
Pick the dates from the pop-up calendars and it will automatically format them into the official standard (like "05 October 2025").

---

## 🖨️ Saving as PDF (IMPORTANT!)

When you're done, click the green **"Save as PDF / Print"** button.

⚠️ **CRITICAL STEP:** When your browser's print window pops up, you **MUST** click on "More Settings" and check the box that says **"Background graphics"**.
If you forget to check this box, your browser will strip the colors right out of the AUST logo to save printer ink!

---

## 💻 Running it offline

If you want to use this without internet:

1. Clone or download this repository.
2. Make sure both `index.html` and `aust_logo.svg` are kept in the same folder.
3. Double-click `index.html` to open it in Chrome, Edge, Safari, or whatever browser you use.

## 🤝 Contributing

If you notice a missing course or an updated lab manual, feel free to fork the repo, add the new course to the `courseDatabase` object inside the `index.html` file, and submit a Pull Request.
