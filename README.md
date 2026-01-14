
SAFEGUARDING WEBSITE
--------------------


**Application Purpose**
The Safeguarding web application is a single-page website designed to raise awareness of safeguarding responsibilities and provide users with a clear, accessible way to report safeguarding concerns.
The site presents essential safeguarding information in a structured format and encourages users to act responsibly by recognising signs of harm and knowing how to report concerns. It also links them to where they can get further information when needed.

**User Value**
This application provides value to the users by:
- Clearly explaining what safeguarding is and why it is important.
- Highlighting key signs to look out for. 
- Providing action steps needed to respond to safeguarding issues.
- Allowing users to submit a concern through a short form.
- The single-page layout ensures smooth navigation and a user-friendly experience without unnecessary page reloads.

**Front-End Design & Accessibility**
- The application uses a one-page layout with a clear navigation menu that links to key sections on the page.
- Semantic HTML elements (e.g. nav, section, footer, headings) are used to improve structure and readability.

Accessibility guidelines were followed:
- Colour contrast was checked using a colour contrast checker, and no WCAG validation errors were identified.
- All images include appropriate alt text.
- Forms include labels and required fields.
- Bootstrap 5 is used to create a responsive layout that adapts to different screen sizes.

**User Experience (UX) Design**
- Content is organised using clear headings and card-based layouts, so it's easier for users to scan through the page.
- Information is prioritised in a way that guides users from basic information to action.
- User-initiated actions (form submission) provide immediate feedback via a success alert (modal) without reloading the page.
- Navigation anchor links allow users to move easily between sections on the page.

**Code Validation & Responsive Design**
- Custom HTML and CSS were validated using the W3C HTML Validator.
- The layout is responsive across screen sizes using Bootstrap’s grid system, responsive utility classes and media queries.
- Navigation and interactive elements function correctly on mobile, tablet, and desktop devices.

**Deployment & Version Control**
- The application was deployed via GitHub.
- Git and GitHub were used for a clear commit history.
- All internal links, navigation anchors, and interactive elements were tested and confirmed to work correctly.

**Screenshots**
- Screenshot 1: *Hero Section – Safeguarding Awareness*
Description: The hero section introduces the safeguarding theme using an inclusive background image and a clear heading.
User Value: Immediately communicates the purpose of the website and guides users toward key safeguarding information.

![screenshot1](assets/screenshots/hero-page.png)

- Screenshot 2: *Key Information Section*
Description: Three Bootstrap cards present What is Safeguarding, Signs to Watch For, and Action Steps, each supported by imagery and structured text.
User Value:
Information is broken into clear, scannable sections, making safeguarding guidance easy to understand and access across devices.

![screeenshot2](<assets/screenshots/key information.png>)

- Screenshot 3: *Report a Safeguarding Concern Form and footer section*
Description: A responsive contact form allows users to submit safeguarding concerns alongside clearly displayed safeguarding lead contact details. The footer contains social media links and copyright information, with external links opening securely in new tabs.
User Value: Offers a straightforward and accessible method for reporting concerns, providing immediate visual feedback upon submission. The footer section ensures consistent navigation, professional presentation, and secure external linking.

![screenshot3](<assets/screenshots/report concerns.png>)

**External Resources Reference**
The following external resources were used:
- [Bootstrap 5.3](https://getbootstrap.com/)
Used for layout, navigation, cards, forms, buttons, and alerts.
- [Font Awesome] (https://fontawesome.com/) Used for icons throughout the application.
- Images [Photos sourced from Freepik:](https://www.freepik.com/)
- Safeguarding Reference Material [UK Government guidance:] (https://www.gov.uk/childcare-parenting/safeguarding-and-social-care-for-children)

**Use of AI Tools**

*AI-Assisted Code Creation*
- AI tools (GitHub Copilot) were used to generate initial content and code structures. The generated output was reviewed and amended to ensure accuracy, accessibility, and alignment with project objectives.
- Chat-gpt was used to support correcting the errors listed on the hmtl validator.

*AI Assisted Debugging*
AI tools were used to identify and resolve issues during development, including:
- Detecting why the background image disappeared after adding a Google Font import (caused by CSS being wrapped incorrectly in style tags).
- Resolving a deployment issue where the hero image did not load due to incorrect folder capitalisation.

*AI-Assisted Optimisation*
AI tools supported improvements to:
- User feedback through dynamic success alerts.
- Code formatting and readability with prettier.

*Reflection on AI’s Impact*
AI tools improved development efficiency by speeding up debugging, reinforcing best practices, and supporting cleaner code structure. Their use allowed more time to focus on accessibility, UX decisions, and assessment alignment rather than repetitive troubleshooting.
