# University-Club-Information-Website
The team has been asked to collaboratively develop a small informational website for a fictional University Student Clubs Portal. The purpose of the website is to introduce different student clubs and provide basic information for new students who want to participate in campus activities.

---

## 🏗️ Project Organization
To ensure the project remains stable, we follow a strict folder structure:

*  `/src` : Contains all HTML pages (Home, Clubs, Events, Join, and Highlights).
*  `/styles` : Contains the global `styles.css` file.
*  `.gitignore` : Prevents system and IDE junk files from cluttering the repository.

---

## 🎨 Design & Style Guide
We aim for a consistent, modern look across all five pages:
*  Colors:  Light Blue, Grey, White, and Black.
*  Typography:  'Playfair Display' for headings and 'DM Sans' for body text.
*  Responsiveness:  Every page must include at least one CSS Media Query to ensure it works on mobile devices.

---

## 🚀 Getting Started (For Team Members)
Follow these steps to set up your local environment:

1. Clone the Repository:
   git clone https://github.com/DevOps-SEG2/University-Club-Information-Website.git
   
2. Enter the Project Directory:
   cd University-Club-Information-Website

3. Switch to the Development Branch:
   git checkout develop

4. Create Your Feature Branch:
   git checkout -b feature/your-page-name

---

## ⚠️ Critical Development Rules
*  CSS Pathing:  All HTML files must link to styles using: 
  <link rel="stylesheet" href="../styles/styles.css">
*  Workflow:  Never push directly to 'main' or 'develop'. Use Pull Requests.
*  Rebase:  Always run 'git rebase origin/develop' before merging to keep history clean.

---