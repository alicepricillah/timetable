# Alice  Osieko - Timetable [2024/2025]

![Timetable Preview](timetable-preview.png "Preview of Timetable Project")

## Overview
This project recreates the 2024/2025 academic year timetable using **HTML** and **CSS**.  
It demonstrates knowledge of HTML tables, CSS styling, and accessibility best practices.

---


## Features
- Fixed layout timetable (not responsive to maintain readability).  
- Clear separation of **days, time slots, and year groups (Yr. 7–11)**.  
- **Merged cells** using `rowspan` and `colspan` for shared activities such as *Devotion*, *Breaks*, and *Gender Meetings*.  
- **Semantic structure** with `<thead>`, `<tbody>`, and `<tfoot>` for clarity.  
- **Uniform borders** and consistent spacing for readability.  
- Special **highlighting** for Breaks, Lunch, and End-of-day Activities.  

---

## Accessibility Considerations
- **Table Headers:** Implemented using `<th>` elements with `scope="col"` and `scope="row"` to help screen readers.  
- **Semantic HTML:** Table is divided into `<thead>` for headers, `<tbody>` for content, and `<tfoot>` for footer notes.  
- **Alt Text:** The timetable preview image (`timetable_preview.png`) includes descriptive `alt` text:  
  > *"Preview of the 2024/2025 School Timetable showing days, periods, and activities for Year 7 to Year 11."*

---

## File Structure

Alice_Osieko/
│
├── index.html # Main timetable file
├── style.css # CSS stylesheet
├── README.md # Documentation (this file)
└── timetable_preview.png # Screenshot of the timetable

---

## Validation
- ✅ HTML validated using [W3C Markup Validator](https://validator.w3.org/)  
- ✅ CSS validated using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)  

---

## Author
Prepared by: *Alice Osieko* 
Approved by: *Mr Chacha*  






