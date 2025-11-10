# Vecta Corp Website Enhancement  
### CS648 – Assignment 10  

## Overview  
This project enhances the **Vecta Corp** website by integrating **jQuery Plugins** and **jQuery UI components** to improve usability, interactivity, and design consistency.  

The goal is to apply various jQuery UI widgets and plugins across the website’s pages—**Home**, **About Us**, **Solutions**, and **Contact Us**—to create a smooth, interactive experience for users.

---

## Features Implemented  

### General (All Pages)
- Added **Tooltip widget** to all navigation menu items.  
  - Each menu item now displays a unique, descriptive tooltip when hovered.  
  - Example:  
    - *Solutions:* “Vecta Corp. offers 3 solutions for prospecting, converting, and retaining customers.”  
  - Applied consistently across all 5 pages of the site.

---

### Home Page
- **Tabs Widget:**  
  - Displays the 3 Vecta Corp. solutions in a horizontal tab layout under the *Our Solutions* heading.  
  - Each tab shows information and an image for the corresponding solution.

- **Accordion Widget:**  
  - Added under *Client Testimonials* to toggle between the 2 testimonials interactively.

---

### About Us Page
- **Tabs Widget (Vertical):**  
  - Organizes the *Management Team* section into 5 vertical tabs, one for each manager.  
  - Clicking a tab reveals that manager’s bio.  

- **Cycle2 Plugin:**  
  - Implemented an **auto-rotating slideshow** for showcasing the new Vecta Corp headquarters.  
  - Includes clickable navigation controls to switch between images.  
  - Images are located in the `/images` folder.

---

### Solutions Page
- **Solutions Content:**  
  - Formatted content under *Our Solutions* heading for clarity and visual appeal.  

- **Quick Navigation (Sticky):**  
  - Integrated a **StikkyNav plugin** to create a floating Quick Nav that stays in place as the user scrolls.  
  - Links allow smooth navigation to specific solution sections on the page.  

- **Back to Top Plugin:**  
  - Added a **smooth scroll “Back to Top” button** for easy navigation back to the top of the page.  

---

### Contact Us Page
Converted all form elements using **jQuery UI** for consistency and improved aesthetics:
- Radio buttons → **jQuery UI radio buttons**  
- Checkboxes → **jQuery UI checkboxes**  
- Dropdown menu → **jQuery UI selectmenu**  
- Submit button → **jQuery UI button**

---

## Technologies Used
- **HTML5 / CSS3**
- **JavaScript / jQuery**
- **jQuery UI**
- **Cycle2 Plugin**
- **StikkyNav Plugin**
- **Back to Top Plugin**


