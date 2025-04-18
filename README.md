# Conference Ticket Generator

This project is a front-end application designed to generate a conference ticket for the "Coding Conf 2025" event. Users can upload their avatar, enter their details, and generate a personalized ticket that is sent to their email address.

## Features
- **Avatar Upload**: Users can upload their photo (JPG/PNG, max 500KB) for the conference ticket.
- **Form Validation**: Ensures that the user provides their full name, email address, and GitHub username.
- **Responsive Design**: The layout adjusts seamlessly across different screen sizes (desktop, tablet, mobile).
- **Ticket Generation**: After submitting the form, a personalized ticket is displayed with the user’s details.
- **Interactive Buttons**: Change or delete the uploaded avatar image.
- **Email Confirmation**: The ticket will be sent to the user's email address after generation.

## Technologies Used
- **HTML**: Used for the structure of the web pages.
- **CSS (SASS)**: Provides styling, including responsive design for different screen sizes.
- **JavaScript**: Handles form validation, avatar upload, and ticket generation logic.

## Project Structure
```
/assets
  /images
    - Various image assets for icons, logos, and backgrounds
  /fonts
    - Fonts used in the project
/css
  - style.css            - Compiled main stylesheet
  - adaptive.css         - Media queries for responsive design
  - style.scss           - SASS source file for main styles
/js
  - app.js               - JavaScript file for form handling, image upload, and ticket generation
index.html               - Main HTML file
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/conference-ticket-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd conference-ticket-generator
   ```

3. Open the `index.html` file in a web browser to view and interact with the conference ticket generator.

4. Upload an avatar image, fill in the required details (Full Name, Email Address, GitHub Username), and click on the "Generate My Ticket" button.

5. Your personalized ticket will be displayed, and a confirmation email will be sent.

## Development Setup
If you want to contribute to the project or make changes locally, follow these steps:

1. **Install dependencies** (if using npm/yarn):
   - This project uses SASS, so you'll need to install Node.js and npm to compile SCSS into CSS.

2. **Run the project**:
   - After setting up dependencies, you can open the `index.html` file directly in the browser.

3. **SASS Compilation**:
   - If you make changes to the `style.scss` file, you need to compile it into CSS using a SASS compiler.
   - Run this command to compile the SCSS:
     ```bash
     sass css/style.scss css/style.css
     ```

## Contributing
Feel free to open issues or submit pull requests if you want to contribute to the project. Any improvements or bug fixes are highly appreciated!

## License
This project is licensed under the MIT License.

## Attribution
Challenge by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge).

