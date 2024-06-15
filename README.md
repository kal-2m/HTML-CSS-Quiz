# HTML/CSS Quiz
 
# Accessibility Quiz Project

This project is a practice quiz designed to test knowledge of HTML and CSS, specifically focusing on accessibility concepts. It includes a form with questions related to HTML and CSS, ensuring accessibility features are properly implemented.

## Project Overview

The project consists of a single HTML file, structured with semantic elements and accessibility considerations:

- **Header:** Contains the project logo, title, and navigation links with access keys.
- **Main:** Contains a form with sections for student information and quiz questions.
- **Footer:** Provides contact information.

### HTML Structure

- **`<header>`:** Includes the logo, project title, and navigation links with access keys for quick access (`INFO`, `HTML`, `CSS`).
- **`<main>`:** 
  - **Student Info Section:** Inputs for name, email, and date of birth.
  - **HTML Questions Section:** Two radio-button questions about HTML elements.
  - **CSS Questions Section:** A dropdown question about CSS properties and a textarea for additional questions.
- **`<footer>`:** Contact information in an address block.

### Accessibility Features

- **Access Keys:** Navigation links have access keys (`i` for INFO, `h` for HTML, `c` for CSS) for keyboard navigation.
- **Labels and Inputs:** Each input has a corresponding label for better form accessibility.
- **ARIA Roles:** Sections have `role="region"` and `aria-labelledby` attributes to enhance accessibility for screen readers.
- **Screen Reader Text:** Added visually hidden text for elements like date of birth to clarify purpose for screen readers.

### Styling

The project includes an external CSS file (`styles.css`) to style the quiz form. Make sure to link this CSS file in the HTML `<head>` section.

## Usage

To use this project, simply open the HTML file in a web browser. You can fill out the form and submit it to the provided action URL for practice purposes.

