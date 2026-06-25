# AUST Cover Page Generator

AUST Cover Page Generator is a simple, browser-based tool that helps students at Ahsanullah University of Science and Technology (AUST) create well-formatted cover pages quickly and easily.

It supports lab reports, open-ended labs (OEL), and theory assignments for both single and group submissions. The layout updates automatically based on the selected submission type, and all formatting happens directly in your browser.

Created by Adittya Sinha Arko.

[Try the Live Demo Here](https://ibuk-i.github.io/aust-cover-page-generator/)

## Key Features

- **Supports multiple submission types**: Use the generator for lab reports, open-ended labs, assignment single submissions, and assignment group submissions.
- **Automatic layout updates**: Labels and page structure adjust automatically according to the selected format.
- **Group submission table**: Displays a clean table for group members, supporting up to 7 members.
- **Custom spacing controls**: Use the sliders to adjust the position of the submission block for better alignment.
- **EEE course database**: Automatically fills in course codes, course names, and experiment titles for EEE courses from 1st to 4th year.
- **Automatic file naming**: Downloads the PDF with a useful file name based on the submission type.
- **Persistent autofill**: Saves your name, student ID, section, group, and member details in your browser.
- **Private and offline-friendly**: No backend is required. Your data stays on your device.

## How to Use

The generator has a clean dark-mode sidebar and a live preview on the right. Any change you make is updated immediately.

### 1. Choose the submission type

Select one of the following options:

- Lab Report (Single)
- Open Ended Lab (Group)
- Assignment (Single)
- Assignment (Group)

If you are making a single submission, you can use the spacing controls to adjust the position of the "Submitted by" section.

### 2. Select the department

- **EEE (default)** keeps the built-in course preset system enabled.
- **Other departments** let you enter a custom department name.

### 3. Use the course presets

Choose the year/semester and course, then select the experiment number. The generator will automatically fill in the matching experiment title.

If an experiment is skipped or reordered, you can use the override option to change the title manually.

### 4. Edit the final values

If a course is missing from the database or you want to use a custom topic, you can type directly into the final fields:

- Course Code
- Course Name
- Experiment Number
- Experiment Name

The values you enter here will appear exactly in the final cover page.

### 5. Enter student details

Your information is saved automatically as you type, so you only need to enter it once.

Depending on the submission type, this section will show either:

- individual name and student ID fields, or
- a table with up to 7 group members

You can also choose whether the "Group No" line should appear on the page.

### 6. Set the dates

Use the date pickers to set the performance date and submission date.

If a date is not needed, you can hide it using the Show option.

## Saving as PDF

When you are ready, click **Save as PDF / Print** at the bottom of the sidebar.

- On desktop, choose **Save as PDF** from the print dialog.
- On mobile, use the browser menu and select **Save as PDF**.

### Important print setting

In the browser print dialog, open **More Settings** and enable **Background graphics**. This is important because it ensures the green colors in the AUST logo print correctly.

## Running Locally

To run the generator on your own computer:

1. Clone or download the repository.
2. Make sure `index.html` and `aust_logo.svg` are in the same folder.
3. Open `index.html` in a modern browser such as Chrome, Edge, Firefox, Brave, or Safari.

## Contributing

If you find a missing course or an updated lab manual, you can fork the repository, update the `courseDatabase` object in `index.html`, and submit a pull request.
