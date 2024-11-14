# Fitness Website
This is a fitness website project titled AK Fitness. It includes a homepage with a header, a navigation menu, a form for user input, and various interactive elements. Below is an overview of the main CSS features used in the project.

## Features
### 1. Layout and Structure
- **Flexbox:** Used for structuring layout elements such as the header (.header), navigation menu (.navbar), and other containers. Flexbox properties like justify-content, align-items, and flex-direction enable responsive and centered alignment of elements.
- **Box Sizing:** The box-sizing: border-box; style is applied globally to ensure consistent padding and borders, simplifying the layout.

### 2. Fonts and Styling
- **Custom Font:** The website imports the Bebas Neue font from Google Fonts for a modern, sleek look.
- **Typography:** Styles for headings and text (h1, label) ensure that the font size and alignment match the site's aesthetic.

### 3. Color and Background
- **Background Image:** A background image (images/bg.jpg) is applied to the entire body to give a fitness-themed ambiance.
- **Invert Filter:** The logo is styled with filter: invert(100%), turning it white to match the dark background, ensuring visibility and contrast.

### 4. Navigation and Buttons
- **Navbar:** The navigation bar uses gap, text-decoration, and color properties. Hover effects and active states are applied to the links for improved user interaction.
- **Button Styling:** Buttons (.btn) are styled with background color, border, padding, and hover effects that change the color scheme, making them interactive and visually appealing.

### 5. Form Styling
- **Form Container:** The main form (.container) has a white border, shadow effect, and rounded corners (border-radius) to stand out against the dark background.
- **Input Fields:** Inputs (input[type="text"], input[type="tel"], input[type="email"]) have padding, borders, and border-radius for a clean and user-friendly appearance.
- **Radio Buttons:** Organized within a radio-group class for horizontal alignment, creating a structured layout for gender selection.

### 6. Responsive Design
- The layout is structured with Flexbox, making it naturally adaptable to different screen sizes. The usage of relative units (%, em) helps in creating a more responsive design that adjusts seamlessly across devices.
