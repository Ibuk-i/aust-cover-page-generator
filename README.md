# AUST Cover Page Generator

A fast, fully automated cover page generator built specifically for students at Ahsanullah University of Science and Technology (AUST).

It can generate properly formatted cover pages for lab reports, open ended labs (OEL), and theory assignments, whether they are single or group submissions. Everything runs in your browser, so after the first load it works offline and does not need any backend or database.

Created by Adittya Sinha Arko.

[Try the Live Demo Here](https://ibuk-i.github.io/aust-cover-page-generator/)

## Key Features

- **Multi-format support** — Switch between lab reports, open ended labs, and assignments. The layout updates automatically to match the selected submission type.
- **Dynamic group tables** — Converts the "Submitted by" section into a clean table for group submissions, supporting up to 7 members.
- **Custom layout sliders** — Adjust top spacing and left/right position in real time to align the page perfectly.
- **Course database** — Automatically fills in course codes, course names, and experiment titles from the EEE department lab manuals for 1st to 4th year.
- **Smart file naming** — Downloads the PDF with a filename based on the submission type.
- **Persistent autofill** — Saves your name, student ID, section, group, and member details in your browser using LocalStorage.
- **Private and serverless** — All code runs locally in your browser. Nothing is sent to a server.

## How to Use

The generator has a dark-mode sidebar. Anything you change on the left updates the live printable A4 preview on the right.

### 1. Choose the submission type

Pick one of these options:

- Lab Report (Single)
- Open Ended Lab (Group)
- Assignment (Single)
- Assignment (Group)

For single submissions, you can use the top spacing and left position sliders to fine-tune the placement of the "Submitted by" section.

### 2. Select the department

- **EEE (default)** keeps the built-in preset system enabled.
- **Other departments** disable the EEE presets and let you enter a custom department name.

### 3. Use the automated presets

Select your year/semester and course, then choose the experiment number. The generator will automatically fill in the matching experiment title from the course database.

If a teacher changes the order or skips an experiment, you can use the override option to replace the title manually.

### 4. Edit the final print values

If a course is missing from the database or you want to use a custom assignment topic, you can type directly into the final fields for:

- Course Code
- Course Name
- Experiment Number
- Experiment Name

Whatever you type here is exactly what will appear in the final output.

### 5. Enter student details

Your details are saved automatically as you type, so you usually only need to enter them once.

Depending on the submission type, this section will either show:

- your individual name and ID, or
- up to 7 group member rows

You can also choose whether the "Group No" line should appear on the page.

### 6. Set the dates

Use the date pickers to set your performance and submission dates.

If a date is not needed, simply turn off its Show option to remove it from the page.

## Saving as PDF

When you're ready, click **Save as PDF / Print** at the bottom of the sidebar.

- On desktop, choose **Save as PDF** from the print destination.
- On mobile, open the browser menu and select **Save as PDF**.

### Important print setting

In the browser print dialog, open **More Settings** and enable **Background graphics**. Without this, the green colors in the AUST logo may not print correctly.

## Run Locally

To run the generator on your own computer:

1. Clone or download the repository.
2. Make sure `index.html` and `aust_logo.svg` are in the same folder.
3. Open `index.html` in a modern browser such as Chrome, Edge, Firefox, Brave, or Safari.

## Contributing

If you notice a missing course or an updated lab manual, feel free to fork the repository, add the new course to the `courseDatabase` object inside `index.html`, and open a pull request.
