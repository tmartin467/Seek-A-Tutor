# Seek-A-Tutor
System Summary: Developed a dynamic, data-driven web application with AI assistance to streamline the process of tracking and displaying tutor availability, absences, and real-time schedules. This tool significantly increases efficiency for both students seeking help and staff managing coverage.

---

## Description
A passion project created to optimize tutor searches and administrative oversight for tutees, tutors, Student Assistants, and Pro Staff. This system replaces manual scheduling checks with a real-time, filterable web interface, drawing schedule data from a JSON source and applying logic to calculate availability and highlight current absences.

---

## Technical Stack
 - Front-end: HTML5, JavaScript (Vanilla JS)

 - Styling: Tailwind CSS (for modern, responsive UI)

 - Data: JSON (for schedule and tutor information)

---

## Installation
This project is a static web application and requires only a web browser to run.

### For end-users:
1. Clone the repository: `git clone https://github.com/tmartin467/Seek-A-Tutor.git`
2. Navigate to the directory: `cd Seek-A-Tutor`
3. Run Locally: Open the main application file, SeekATutor.html, directly in your web browser (e.g., Google Chrome, Firefox).

### For contributors:
1. Follow steps 1 and 2 above (for end-users).
2. Open the project folder in your preferred code editor (VS Code, Sublime Text, etc.).
3. Modify the HTML, JavaScript within <script> tags, or the tutorData.json file.
4. To view changes, simply refresh SeekATutor.html in your browser.

---

## Usage
For Tutees/Students:
  Find an available tutor for a specific subject (e.g., MATH 150).

  Steps:
  1. Use the Subject Search bar to type in the course name.
  2. Use the Day Filter to view only today’s or future schedules.
  3. View list of available tutors (in green or upcoming in blue) to choose a tutor that
     corresponds to your needs. (e.g.: Need a tutor for Calculus on Wednesday)

For Pro Staff/Admin:
  Check real-time coverage and absences.

  Steps:
  1. Should automatically pop up on "Current Day" schedule.
  2. Outlines the current schedule of tutors available, upcoming, and unavailable.
  3. Scroll to the bottom and click "Admin Access: Manage Absences & Shifts"
  4. Input passcode to allow for changes including: Absences, Temporary Shifts,
     Additional Tutor Notes (if needed), AND/OR clear all Temporary Shifts or
     Notes.
