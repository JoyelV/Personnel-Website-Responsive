# Joyel Varghese Portfolio

This project is a personal portfolio website for Joyel Varghese, showcasing his background, skills, projects, and contact information. The website is built using HTML, CSS, and JavaScript, with a responsive design optimized for mobile, tablet, and desktop devices. It features a clean, modern layout with interactive elements such as a tabbed about section, a mobile-friendly sidebar menu, and a contact form integrated with Google Sheets.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Responsive Design](#responsive-design)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Navigation Bar**: A responsive navbar with a logo, menu items (Home, About, Fun Facts, Skills, Projects, Contact), and a toggleable sidebar menu for mobile devices.
- **Header Section**: A full-screen hero section with a background image and Joyel's name for a professional introduction.
- **About Section**: Includes a profile image, bio, and tabbed content for programming languages, education, certifications, and software skills.
- **Fun Facts Section**: Displays interesting tech-related facts in a grid layout with Font Awesome icons.
- **Skills Section**: Highlights expertise in front-end, back-end, and Android app development with links to learning resources.
- **Projects Section**: Showcases projects with images, descriptions, and GitHub links, featuring hover effects for interactivity.
- **Contact Section**: Provides contact details, social media links, a downloadable resume, and a form that submits data to Google Sheets.
- **Smooth Scrolling**: Enabled for navigation links to provide a seamless user experience.
- **Interactive Elements**: Hover effects on project cards, social icons, and buttons, along with a dynamic tab system in the About section.

## Technologies Used
- **HTML5**: For the structure of the web page.
- **CSS3**: For custom styling, including grid layouts, hover effects, and media queries for responsiveness.
- **JavaScript**: For interactive features like tab switching, mobile menu toggling, and form submission to Google Sheets.
- **Font Awesome**: For icons in the navbar, skills, fun facts, and contact sections.
- **Google Sheets API**: For handling contact form submissions.
- **External Resources**:
  - Font Awesome via CDN (`https://kit.fontawesome.com/0d8c6deebc.js`).
  - External images for the logo, background, profile, and project thumbnails.
  - Resume PDF for download.

## File Structure
```
├── index.html        # Main HTML file
├── style.css         # Custom CSS for styling
├── images/           # Folder containing images (logo, background, profile, project thumbnails)
│   ├── logo.jpeg
│   ├── background1.png
│   ├── phone-background-1.jpg
│   ├── user1.jpeg
│   ├── work-1.png
│   ├── work-2.png
│   └── Resume.pdf
├── script.js         # JavaScript for interactivity (embedded in index.html)
└── README.md         # Project documentation
```

## Setup Instructions
1. **Clone or Download the Repository**:
   ```bash
   git clone <repository-url>
   ```
   Alternatively, download the project files as a ZIP and extract them.

2. **Ensure Image Assets**:
   - Place all required images (`logo.jpeg`, `background1.png`, `phone-background-1.jpg`, `user1.jpeg`, `work-1.png`, `work-2.png`, `Resume.pdf`) in the `images/` folder.
   - Update image paths in `index.html` if necessary.

3. **Open the Project**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser to view the portfolio.

4. **Dependencies**:
   - No local dependencies are required, as Font Awesome is loaded via CDN.
   - Ensure an active internet connection for the Font Awesome CDN and Google Sheets API to function.
   - For the contact form to work, ensure the Google Sheets script URL (`https://script.google.com/macros/s/...`) is correctly configured with a valid Google Apps Script.

## Usage
- **Navigation**: Use the navbar to jump to different sections (Home, About, Fun Facts, Skills, Projects, Contact). On mobile devices, click the hamburger icon to open the sidebar menu.
- **About Section**: Click the tabs (Programming Languages, Education, Certifications, Software) to view relevant details.
- **Fun Facts**: Read tech-related trivia presented in a grid layout.
- **Skills**: Explore Joyel's skills with links to external learning resources.
- **Projects**: Hover over project cards to reveal descriptions and click the GitHub icon to visit project repositories.
- **Contact**: Use the form to send a message (submits to Google Sheets), view contact details, or download the resume. Social media icons link to Joyel's profiles.
- **Smooth Scrolling**: Clicking navbar links smoothly scrolls to the respective section.

## Responsive Design
The website is optimized for various screen sizes:
- **Mobile (≤600px)**:
  - Background image switches to a mobile-optimized version (`phone-background-1.jpg`).
  - Navbar collapses into a sidebar menu, toggled by hamburger and close icons.
  - About, contact, and other sections stack vertically for better readability.
  - Font sizes and margins are adjusted for smaller screens.
- **Tablet and Desktop (>600px)**:
  - Full-screen background image (`background1.png`) and grid layouts for skills, fun facts, and projects.
  - About section displays image and text side by side.
  - Contact section splits into left (details) and right (form) columns.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code follows the existing style, includes comments where necessary, and maintains responsiveness.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Created with ❤️ by Joyel Varghese*
