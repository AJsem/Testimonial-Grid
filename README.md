# Testimonial-Grid
Frontend Mentor- Testimonial Grid Challenge

Testimonials Grid - Documentation

1. Project Overview
This project is a Testimonials Grid layout built using HTML and CSS, following the Frontend Mentor challenge. The goal is to create a responsive grid displaying user testimonials with different layouts on various screen sizes.

2. File Structure
bash
Copy
Edit
/Testimonials-Grid/
│── index.html           # Main HTML file
│── style.css            # Stylesheet
│── images/              # Folder containing profile images and favicon
│── README.md            # Documentation and project details (optional)
3. HTML Structure
The HTML file (index.html) contains:

A main container (.main-container) that holds all testimonials.
Two primary sections:
Left Container (.left-container)
Contains two sub-sections (.top-left-container, .bottom-left-container).
Each sub-section contains two testimonial cards.
Right Container (.right-container)
Contains a single testimonial card.
Each testimonial card consists of:
Profile picture (img tag)
User details (.name-status)
Testimonial title (h2)
Testimonial content (p.innerPTag)
The attribution section contains a reference to Frontend Mentor and the developer's name.
Semantic Structure
html
Copy
Edit
<div class="main-container">
    <div class="left-container">
        <div class="top-left-container">
            <div class="left all-container"> ... </div>
            <div class="right all-container"> ... </div>
        </div>
        <div class="bottom-left-container">
            <div class="left all-container"> ... </div>
            <div class="right all-container"> ... </div>
        </div>
    </div>
    <div class="right-container all-container"> ... </div>
</div>
4. CSS Styling (style.css)
Fonts: Imported from Google Fonts (Barlow Semi Condensed).
Global Styling:
box-sizing: border-box;
margin: 0; padding: 0;
Main Layout:
Uses Flexbox (display: flex) for responsiveness.
Mobile-first approach (default is block, changes to flex on larger screens).
Testimonial Cards:
Different background colors for variety.
Padding and border-radius for a clean UI.
Text hierarchy: User names are bold, testimonials have larger font sizes.
Responsive Design:
Uses media queries for adjusting layouts on tablet and desktop screens.
Mobile: Cards stack vertically.
Desktop: Cards form a grid layout.
5. Images
The images/ folder contains:

Profile pictures: image-daniel.jpg, image-jonathan.jpg, etc.
Favicon: favicon-32x32.png
6. Accessibility Considerations
Alt attributes on images.
Semantic HTML for better screen reader support.
Readable font sizes.
7. Future Improvements
Add dark mode support.
Implement animations for hover effects.
Optimize for faster loading times.
