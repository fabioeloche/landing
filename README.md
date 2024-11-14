# N2F Expense Report Website

The N2F Expense Report Website is designed to showcase a user-friendly platform that simplifies expense report management for businesses of all sizes. The main objective of this site is to provide users with a clear understanding of the platform's features, including receipt scanning, corporate card integration, and seamless synchronization with existing company software. The website guides users through the software's benefits and offers a simple way to sign up for a free trial.

![Responsice Mockup](/assets/screenshots/n2f_responsive.png)
The live version of the site can be found at: [N2F Expense Report](https://fabioeloche.github.io/expense_report_landing/index.html).

## Table of Contents
1. [Project Overview](#project-overview)
2. [Design](#design)
   - [Color Scheme](#color-scheme)
   - [Typography](#typography)
   - [Layout](#layout)
3. [Features](#features)
   - [Key Features](#key-features)
4. [Page Structure](#code-structure-explanation)
   - [Header](#header)
   - [Main Content](#main-content)
   - [Hero Section](#hero-section)
   - [Benefits Section](#benefits-section)
   - [Features Section](#features-section)
   - [Footer](#footer)
5. [Future Enhancements](#future-enhancements)
6. [Testing](#testing)
   - [Navigation Bar](#navigation-bar)
   - [Landing Page (index.html)](#landing-page-indexhtml)
   - [Features Page (features.html)](#features-page-featureshtml)
   - [Signup Page (signup.html)](#signup-page-signuphtml)
   - [General Tests](#general-tests)
   - [Validator Testing](#validator-testing)
   - [Unfixed Bugs](#unfixed-bugs)
7. [Deployment](#deployment)
   - [Local Development](#local-development)
      - [Forking the Repository](#forking-the-repository)
      - [Cloning the Repository](#cloning-the-repository)
8. [Technologies Used](#technologies-used)
9. [Credits](#credits)

## Project Overview
The N2F Expense Report Website serves as a hub for businesses to learn about the platform’s key features and quickly sign up for a trial. N2F enables companies to save time and resources by automating the process of tracking expenses, generating corporate cards, and integrating with existing accounting software. The website is designed to be responsive and visually appealing, allowing users to easily access the information they need on any device.

## Design

### Color Scheme
The website uses a sleek black background with white text, providing a clean and professional look. Orange and yellow gradients are used to highlight buttons and headers, adding visual emphasis to important calls-to-action, such as the sign-up button.
![Features Image](/assets/screenshots/color_scheme.png)

### Typography
The website uses two fonts from Google Fonts:
- **Oswald** for headings, providing a bold and modern look.
- **Lato** for body text, ensuring readability across different screen sizes and devices.

### Layout
The layout is designed to be responsive, ensuring a consistent user experience across desktops, tablets, and mobile devices. The grid system allows content to be displayed clearly, with enough space for users to navigate the site effortlessly.

## Features

### Key Features

The website is designed to guide users through a seamless journey:
- **Homepage:** Visitors are welcomed with an engaging hero video and clear messaging about the platform’s key benefits. A prominent "Sign Up" button encourages users to start their free trial.

![Homepage](/assets/screenshots/index.html_page.png)

- **Features Page:** The features are outlined in detail, with easy-to-understand descriptions of each. This page focuses on the time and cost savings offered by N2F and the ease of integrating it with existing systems.

![Features Image](/assets/screenshots/features.html_Page.png)

- **Sign-Up Page:** The sign-up process is kept simple, with a form that asks for basic details such as the user’s first name, last name, and email address. The goal is to reduce friction and make it easy for potential users to get started.

![Sign Up](/assets/screenshots/signup.html_page.png)

- **Footer:** Available on every page, the footer provides links to N2F’s social media channels (Twitter, Facebook, YouTube) for further engagement.

## Page Structure

### Header
The header section of the site includes the logo and navigation menu. The navigation menu contains links to the Home, Features, and Sign-Up pages. On mobile devices, the navigation collapses into a menu that can be toggled by clicking an icon. This ensures that the site remains easy to navigate, regardless of the device being used.

![Header](/assets/screenshots/header-section.png)

### Main Content
The main content of the site is divided into various sections, each with a clear focus. These sections include the hero, benefit, features, and footer sections.

### Hero Section
The hero section includes a full-screen video that auto-plays when the page loads. This video provides a dynamic and engaging introduction to N2F’s key features. Positioned over the video is a brief message that highlights the platform’s core benefit: saving time and money on expense management.

### Benefits Section
The benefits section emphasizes the time and cost savings that N2F can provide. A clear message is displayed, along with a button that leads users directly to the sign-up page. Additionally, a demo video is embedded to showcase how the platform works in a real-world scenario.

![Video](/assets/screenshots/hero-section-video.png)

### Features Section
The features section uses a grid layout to showcase N2F’s five core features:
1. **Smart Scan** – Quickly scans receipts.
2. **Receipt Storage** – Stores receipts in compliance with legal requirements.
3. **Corporate Payment Cards** – Issuance of cards for business trips.
4. **Integration with Company Software** – Seamless integration with accounting software.
5. **Approval Workflow** – Automates the approval of reimbursements.

This section is designed to be easily scannable, allowing users to quickly grasp the platform’s main selling points.

![features](/assets/screenshots/features_section.png)

### Footer
The footer provides links to N2F’s social media pages, encouraging users to follow and engage with the platform. It also reinforces the professionalism of the site by maintaining consistency across all pages.

![footer](/assets/screenshots/footer_section.png)

## Future Enhancements 
- **Enhanced Analytics Dashboard:** In future iterations, a detailed analytics dashboard could be added, providing businesses with insights into their spending patterns and helping them make data-driven decisions.
- **Multi-language Support:** To accommodate a global audience, language localization can be implemented, allowing users to view the site and use the platform in their preferred language.
- **Additional Payment Integrations:** More corporate payment card providers could be integrated into the platform, expanding N2F’s reach.

## Testing

### Navigation Bar:
- Tested all navigation bar elements across the three pages: `index.html`, `features.html`, and `signup.html` for proper functionality.
- Verified hover effects for navigation links on all pages.
- Confirmed the navigation bar remains fully responsive across various screen sizes.

### Landing Page (index.html):
- Tested the call-to-action button for smooth interaction and redirection to the signup page.
- Checked social media icons to ensure they open in a new tab and redirect to the correct external pages.
- Ensured the page layout and elements (e.g., text, images, buttons) display properly on different browsers (Chrome, Safari, MS Edge) and devices (desktop, tablet, mobile).
- Tested the favicon appearance across all pages and confirmed it loads correctly.

### Features Page (features.html):
- Verified the responsiveness of the features section across various screen sizes (mobile, tablet, and desktop).
- Checked the images and ensured proper alignment on all devices.

### Signup Page (signup.html):
- Tested the form with both valid and invalid inputs for fields like First Name, Last Name and Email to ensure validation functions as expected.
- Verified that the Email field requires correct syntax (e.g., with an "@" symbol) and displays error messages if incorrect.
- Ensured that the "Submit" button only works when required fields are filled out correctly.
- Tested responsiveness of the form and page across different devices and screen sizes.

### General Tests:
- Ensured all links across the pages function correctly, opening external links in a new tab where necessary.
- Verified that the 404 error page displays appropriately for non-existent URLs.
- Checked the website's responsiveness, confirming it works seamlessly across different browsers (Chrome, Safari, MS Edge) and devices (desktop, tablet, mobile).
- The site was tested on all major browsers, including Google Chrome, Firefox, Microsoft Edge, and Safari. No significant issues were found, and the site performed consistently across all platforms.

### Validator Testing
- **HTML Validation:** The HTML files were validated using the W3C HTML Validator, and no significant issues were found. [Test W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-fabioeloche-expenserepo-cgapq5wdey2.ws-eu116.gitpod.io%2Findex.html)
- **CSS Validation:** The CSS files passed through the W3C Jigsaw Validator with no errors. [Test (Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F8000-fabioeloche-expenserepo-cgapq5wdey2.ws-eu116.gitpod.io%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=it)
- **Accessibility Testing:** The website was evaluated using Lighthouse, achieving high scores in accessibility and performance.

![Accessibility](/assets/screenshots/lighthouse-report.PNG)

### Unfixed Bugs
- **Legacy Browser Support:** Older versions of Internet Explorer do not fully support certain CSS3 features such as flexbox and grid. As a result, the layout may not appear as intended on these browsers.

# Deployment

The website is deployed using GitHub Pages. Follow these steps to deploy the project:

1. Log in (or sign up) to GitHub.
2. Go to the repository: [fabioeloche/expense_report_landing](https://github.com/fabioeloche/expense_report_landing).
3. Navigate to the repository’s **Settings** tab.
4. Under the **Code and Automation** section, select the **Pages** option.
5. From the source dropdown, select the **main branch** and save the settings.
6. The site will be deployed within a few minutes. The live version will be accessible at the provided URL once the deployment is complete.

## Local Development

### Forking the Repository

To fork this repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository: [fabioeloche/expense_report_landing](https://github.com/fabioeloche/expense_report_landing).
3. Click the **Fork** button in the top right corner of the page.

### Cloning the Repository

To clone the repository to your local machine:

1. Log in (or sign up) to GitHub.
2. Go to the repository: [fabioeloche/expense_report_landing](https://github.com/fabioeloche/expense_report_landing).
3. Click on the **Code** button, select the cloning method (HTTPS, SSH, or GitHub CLI), and copy the link provided.
4. Open your terminal and navigate to the directory where you want to clone the repository.
5. Type the following command into the terminal:
   ```bash
   git clone <https://github.com/fabioeloche/expense_report_landing>

The live version of the site can be found at: [N2F Expense Report](https://fabioeloche.github.io/expense_report_landing/index.html).

## Technologies Used
- **HTML5:** For structuring the content of the website.
- **CSS3:** For styling the website and creating responsive layouts.
- **Font Awesome:** For adding social media icons to the footer.
- **Google Fonts:** For the Oswald and Lato fonts used throughout the site.
- **GitHub Pages:** For hosting the live version of the website.

## Credits

### Content & Design Inspiration
The initial layout of the menu and header was inspired by the Love [Running project](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/3.1-setting-up-the-basic-html-structure) but has been significantly modified for our purpose. Unlike Love Running, our project uses a black and orange color scheme with gradients, introduces a "Features" section and a video section, includes background and header videos, interactive buttons with hover effects, and focuses on presenting an app for recording business expenses and travel receipts rather than a sports-related theme.

### Video Background
The background video is available for licensing at [Adobe Stock](https://stock.adobe.com/it/video/close-up-of-an-asian-young-man-scaning-the-receipts-from-stores-with-his-mobile-application-in-his-car-after-work-transferring-money-between-accounts-qr-code-scanning-saving-money-deals-coupons/395369427). The purchase of the license will be completed upon the official publication of the website.

### Images & Content
The images and content of the website were provided by the company, available at [Link](https://www.n2f.com/it/nota-spese/).



