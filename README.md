# CirclePe Assignment


## Project Overview
This project is a responsive website implementation based on the provided Figma design and prototype. The website has been designed to be fully responsive across different screen sizes, ensuring a seamless user experience on mobile, tablet, and desktop devices. The implementation includes pixel-perfect design, transitions, animations, cross-browser compatibility, performance optimization, and accessibility considerations.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed on your system:

 - Node.js (version 18 and above)
 - npm (version 6 or above)
 - VS Code ( or any other code editor)

### Installation

Follow these steps to set up the project locally:

  1. Clone the repository:
     ```
     
       git clone https://github.com/mavidishu/CirclePe_Assignment.git
     
     ```
  2. Navigate to the Project Directory:

     ```
     
       cd CirclePe_Assignment
     
     ```
  3. Install Dependencies:

     ```
     
       npm install
     
     ```
  4. Run the Project Locally:

     ```
     
       npm run dev
     
     ```

### File Structure
  ```
    CirclePe-Assignment/
    │
    ├── public/
    │   ├── index.html          # Main HTML file
    │   ├── favicon.ico         # Website favicon
    │   └── assets/             # Public assets like images, fonts
    │       ├── images/
    │       └── fonts/
    │
    ├── src/
    │   ├── assets/             # Source assets like images, fonts, etc.
    │   │   ├── images/
    │   │   └── fonts/
    │   ├── components/         # Reusable components (Header, Footer, etc.)
    │   │   ├── Header.js
    │   │   ├── Footer.js
    │   │   └── Circle.js       # Example component (Circle)
    │   ├── pages/              # Pages for the application (Home, About, etc.)
    │   │   ├── Home.js
    │   │   └── About.js
    │   ├── styles/             # Global and component-specific styles
    │   │   ├── main.css        # Global styles
    │   │   ├── header.css      # Header-specific styles
    │   │   └── circle.css      # Circle-specific styles
    │   ├── App.js              # Main application component
    │   ├── index.js            # Entry point for React
    │   └── utils/              # Utility functions (optional)
    │
    ├── .gitignore              # Git ignore file
    ├── package.json            # NPM package dependencies and scripts
    ├── README.md               # Project README file
    └── webpack.config.js       # Webpack configuration (if applicable)
  ```

### Technologies Used
 - HTML5
 - CSS3
 - JavaScript (ES6+)
 - React.js
 - Bootstrap (for consistent styling)
 - Framer Motion (for animations)

### Challenges Faced
 - *Responsive Design:* Ensuring that all elements resize and reflow correctly across different screen sizes was a challenge, particularly with complex layouts.
 - *Cross-Browser Compatibility:* Testing and fixing issues across different browsers required significant effort.
 - *Performance Optimization:* Balancing visual fidelity with performance, especially on slower network connections, was a challenge.

