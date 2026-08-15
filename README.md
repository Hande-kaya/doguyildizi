# Doğu Yıldızı Corporate Website

A bilingual corporate website developed for **Doğu Yıldızı Maden Turizm Kuyumculuk Lojistik Danışmanlık İç ve Dış Ticaret A.Ş.**

This website was developed as part of my internship project. It presents the company, its business activities, services, and contact information in both Turkish and English.

## Features

- Turkish and English language support
- Responsive navigation bar
- Compact language selector
- Mobile-friendly layout
- Corporate homepage
- About Us page
- Services page
- Contact page
- Formspree contact form integration
- Google Maps integration
- Thank-You pages after successful form submissions
- Responsive Bootstrap components
- CSS animations and transition effects
- Scroll-based animations using JavaScript
- Animated counters and interactive visual elements

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- Formspree
- Google Maps
- Git
- GitHub

## Project Structure

    doguyildizi/
    │
    ├── css/
    │   └── styles.css
    │
    ├── en/
    │   ├── about.html
    │   ├── contact.html
    │   ├── index.html
    │   ├── services.html
    │   └── thank-you.html
    │
    ├── images/
    │
    ├── about.html
    ├── contact.html
    ├── index.html
    ├── services.html
    ├── thank-you.html
    └── README.md

## Website Pages

### Turkish Version

The Turkish version is located in the root directory and includes:

- `index.html` - Homepage
- `about.html` - About Us
- `services.html` - Services
- `contact.html` - Contact
- `thank-you.html` - Post-submission confirmation page

### English Version

The English version is located inside the `/en/` directory and includes:

- `en/index.html` - Homepage
- `en/about.html` - About Us
- `en/services.html` - Services
- `en/contact.html` - Contact
- `en/thank-you.html` - Post-submission confirmation page

## Bilingual Structure

The website was designed as a bilingual project with separate Turkish and English pages.

A language dropdown in the navigation bar allows users to switch between the two language versions.

The English pages are stored inside the `/en/` directory, while shared resources such as images and CSS files are reused across both language versions.

Relative paths such as `../images/` and `../css/styles.css` are used inside the English directory to access shared resources.

## Responsive Design

The website was developed using Bootstrap's responsive grid system together with custom CSS.

The interface was tested on different viewport sizes using browser Developer Tools.

Responsive behavior was implemented for:

- Navigation bar
- Language selector
- Hero sections
- Service cards
- Image layouts
- Contact forms
- Google Maps
- Thank-You pages
- Desktop, tablet, and mobile screen sizes

## Contact Form

The contact forms are integrated with **Formspree**.

JavaScript is used to submit the form asynchronously using:

- `FormData`
- `fetch()`
- Formspree API responses
- Error handling
- Success redirects

After a successful submission, users are redirected to the corresponding Thank-You page.

The Turkish contact form redirects to the Turkish confirmation page, while the English contact form redirects to the English version.

## Interactive Features

Several JavaScript and CSS-based interactive elements were implemented throughout the website.

These include:

- Scroll-based fade-in animations
- `IntersectionObserver` viewport detection
- Animated KPI counters
- Hero image animation
- Responsive navigation menu
- Language dropdown
- Animated contact-page visual elements
- Automatic Thank-You page redirects

## Thank-You Pages

Dedicated confirmation pages were created for both language versions.

The pages provide:

- Submission confirmation message
- Link back to the homepage
- Link back to the Contact page
- Automatic homepage redirect after five seconds

The automatic redirect is implemented using JavaScript's `setTimeout()` function.

## About the Company

Doğu Yıldızı Maden Turizm Kuyumculuk Lojistik Danışmanlık İç ve Dış Ticaret A.Ş. was established in Istanbul in 2020.

The company operates in domestic and international trade and focuses on the import, supply, and wholesale distribution of industrial machinery, technical components, and related equipment.

The website was designed to present these activities through a modern and professional corporate interface.

## Development Process

The website development process included:

1. Requirement analysis and technical planning
2. Project folder and page structure creation
3. Shared navigation and footer development
4. Homepage design and visual styling
5. Turkish page development
6. Responsive design testing
7. Debugging and browser testing
8. English page localization
9. Formspree and Google Maps integration
10. Post-submission user experience development
11. Cross-language consistency testing
12. Git and GitHub version control setup
13. Repository documentation

## Version Control

Git is used for local version control and GitHub is used to host and manage the project repository.

The project uses the `main` branch.

Typical development workflow:

    git status
    git add .
    git commit -m "Commit message"
    git push origin main

Version control makes it possible to track project changes, maintain development history, and keep the local project synchronized with the remote GitHub repository.

## Repository Purpose

This repository contains the source code of the Doğu Yıldızı corporate website developed during my internship.

It also serves as documentation of the development process and demonstrates practical experience with:

- Frontend development
- Responsive web design
- Multilingual website development
- JavaScript interaction
- Third-party service integration
- Testing and debugging
- Git version control
- GitHub project management

## Author

Developed by **Hande Kaya** as part of a Computer Engineering internship project.
