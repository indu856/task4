Comapny-Codetech
Name-Sibyala Indu Priya
Task4-Chrome Time Tracker Extension
## Chrome Time Tracker Extension
Description
This project is a Chrome Extension designed to help users track the time they spend on websites, enabling better productivity and time management. Named Chrome Time Tracker, it provides a lightweight and user-friendly popup interface that keeps users aware of their browsing habits.
## What I Have Done
The extension is developed using standard web technologies such as HTML, CSS, and JavaScript. The primary components of the extension include:
Popup Interface (popup.html): A minimal and intuitive UI that shows the tracking status.
JavaScript Logic (popup.js, background.js, content.js): These files contain the logic to monitor active tabs, track time spent, and update the popup dynamically.
Manifest File (manifest.json): Defines the metadata, permissions, background scripts, and icons required for the Chrome extension to function properly.
Category Handling (categories.json): Helps categorize different types of websites for better analysis (e.g., social media, work, entertainment).
Icon Integration: The project includes a custom PNG icon (icon48.png) located in the icons/ folder, used for the extension icon visible in the browser toolbar.
The extension uses the chrome.tabs and chrome.runtime APIs to detect active tabs and monitor the amount of time each tab remains in focus. The popup updates dynamically using DOM manipulation via JavaScript.

## Tools & Technologies Used
HTML/CSS/JavaScript: For building the popup and handling logic.
Chrome Extensions API: Core APIs used include:
chrome.runtime for background communication
chrome.tabs for monitoring active tab activity
Visual Studio Code (VS Code): Used as the code editor during development.
JSON: Used for defining categories and manifest structure.
Windows PowerShell: For testing and running the extension locally.
Chrome Browser: For testing and deployment of the extension.

## Where It Can Be Used
This extension is ideal for:
Students: To monitor time spent on educational vs. non-educational sites.
Remote Workers/Freelancers: To keep track of productive vs. unproductive hours.
Organizations: To analyze time spent by employees (if integrated in a corporate setup).
Anyone Looking to Improve Productivity: Helps develop awareness of online time usage.

## How It Works
Tracking Time: When the user installs and activates the extension, it begins tracking the time spent on each website by monitoring the active tab.
Popup UI: The user can click on the extension icon in the Chrome toolbar to open the popup and see the current tracking status.
Category Insight (optional extension): Time data can be grouped into categories using categories.json, allowing for visual summaries or detailed logs in future upgrades.
Icon Usage: The PNG icon is placed in the icons directory and is used in the manifest to appear in the Chrome toolbar.

## Future Enhancements
Add visual charts and summaries of time spent.
Export data as CSV or JSON.
Add pause/resume and reset functionality.
Sync tracking data across devices using Chrome sync storage.
UI improvements with animations and advanced styling.











OUTPUT:
<img width="1919" height="1076" alt="Image" src="https://github.com/user-attachments/assets/6a2cbc73-e25d-4f13-8eae-d24f5ce07b3d" />
