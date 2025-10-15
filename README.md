Savoria - A Responsive Restaurant Website
Screenshot (78)
A modern, fully responsive, single-page marketing website for a fictional restaurant named "Savoria." Built with HTML, CSS, JavaScript, and Bootstrap 5, this project provides a professional and attractive online presence for a culinary establishment.

✨ Features
Fully Responsive Design: Looks great on mobile phones, tablets, and desktops.
Sticky Navigation: A navigation bar that stays at the top of the page with smooth-scrolling links and active section highlighting.
Dynamic "Today's Special": A special badge automatically appears on a specific menu item based on the day of the week.
Dark Mode Toggle: A user-friendly switch to toggle between light and dark themes, with the user's preference saved in their browser.
Interactive Gallery: An elegant image grid with a lightbox modal for viewing larger images.
Testimonial Carousel: A rotating carousel to display customer reviews.
Client-Side Form Validation: A contact/reservation form with JavaScript validation to ensure all required fields are filled out correctly.
Accessibility & SEO Ready: Built with semantic HTML, proper alt tags, and essential meta tags for better search engine visibility.
🛠️ Technology Stack
HTML5: For the structure and content of the website.
CSS3: For custom styling, animations, and the dark mode theme.
JavaScript (ES6+): For dynamic functionality like form validation, active navigation, and the theme switcher.
Bootstrap 5: For the responsive grid system, core components (Navbar, Carousel, Modal), and utility classes.
Font Awesome: For social media and contact icons.
Google Fonts: For elegant and readable typography (Playfair Display and Roboto).
📂 Project Structure
The project follows a simple and organized folder structure:

savoria-restaurant/ │ ├── 📂 assets/ │ └── 📂 images/ │ ├── favicon.ico │ ├── favicon.svg │ └── ... (your images here) │ ├── 📂 css/ │ └── style.css │ ├── 📂 js/ │ └── script.js │ ├── index.html └── README.md

🚀 Getting Started
No complex setup is required. Simply clone or download the repository and open the index.html file in your favorite web browser.

Clone the repository (optional):
git clone [https://your-repository-url.git](https://your-repository-url.git)
Navigate to the project directory:
cd savoria-restaurant
Open index.html:
Right-click on the index.html file and choose "Open with" your preferred browser (e.g., Chrome, Firefox).
🎨 Customization Guide
This template is designed to be easily customized.

1. Changing Text and Content
All text content, including the restaurant name, tagline, menu items, and testimonials, can be edited directly in the index.html file.

2. Updating Images
Place all your images in the assets/images/ directory.
Update the src attribute of the <img> tags in index.html to point to your new image files. Placeholder images are from picsum.photos.
3. Modifying Colors and Fonts
The primary color scheme and fonts are defined as CSS variables at the top of the css/style.css file.
:root {
    --primary-color: #c08c4d;
    --secondary-color: #333;
    --heading-font: 'Playfair Display', serif;
    --body-font: 'Roboto', sans-serif;
}
Simply change these variable values to update the look and feel across the entire site.
4. Updating the Google Map
Go to Google Maps.
Search for your restaurant's address.
Click "Share" and then "Embed a map."
Copy the HTML <iframe> code provided.
Paste this code into the div with the class map-responsive in the Contact section of index.html.
5. Changing "Today's Special" Day
The special is currently set to appear on Wednesday. You can change this in js/script.js.
Find the line if (dayOfWeek === 3 && specialItem).
Change the number 3 to your desired day (0=Sunday, 1=Monday, 2=Tuesday, etc.).
