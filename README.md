# Jumpway Website Version 2
Becuase the previous version was made with HTML, CSS and JS (and only had basic wireframe designing done on AdobeXD), there were many inconsistencies between instances of the same componenet, other inconsistent layout/ design issues, and would take very long to load between pages. I decided to recreate the website **Figma and React JS** to resolve some of these issues. 

## Main Changes
- From HTML, CSS, JS to **React JS** (allowed to convert page into an SPA, use of components for consistency, can now use React hooks to control the page better)
- Ensured that paddings were consistent from page to page
- Reorganized CSS files into modules instead of one massive css file for all styling
- Addition of useState hook to create smoother slideshows or changes of display of components onClick

## Screenshots
| Before | After |
| ------------- | ------------- |
| **Footer**: inconsistent text, misaligned columns, inconsistent from page to page| **Footer**: improved alignment, readability, consistencey|
| <img width="600" alt="image" src="https://github.com/user-attachments/assets/349d964e-aca0-44b6-a6d0-166cb73dd734">| <img width="600" alt="image" src="https://github.com/user-attachments/assets/fe06ac2f-2372-4c6c-bb76-d878d84b205d">  |
| **Service Component**: inconsistent layout with extra space between mask and image when mouse hovers over middle row instances | **Service Component**: all instnaces had same layout just different content, less repetitive coding, hover effects worked smoothly across all instances |
| <img width="600" alt="image" src="https://github.com/user-attachments/assets/7fec2f28-9c73-4111-9ee5-05b315992fa1"> | <img width="600" alt="image" src="https://github.com/user-attachments/assets/6a0081d9-f518-47a3-bba9-d74b23708ecc">| 
| **Single CSS File** | **CSS Modules** |
|1 "website.css" file for all styles with almost 3000 lines of code| Several CSS module files for each component each with about 100-300 lines of code|


