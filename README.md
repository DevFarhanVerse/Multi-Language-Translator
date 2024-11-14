# Multi-Language Translator

This project is a web-based multilingual translation application designed to translate English text into multiple languages. Built using HTML, JavaScript, and Bootstrap for styling, the app supports translations into Italian, Spanish, French, German, and Portuguese.

## Features
- **Source Language**: Currently supports English as the source language.
- **Target Languages**: Translates text into Italian, Spanish, French, German, and Portuguese.
- **Real-Time Translation Result**: Displays the translation result dynamically on the page.
- **Responsive Design**: Utilizes Bootstrap for a user-friendly, responsive interface.

## Project Structure
- **index.html**: Main HTML file with a form for language selection and text input.
- **styles.css**: Custom CSS for additional styling.
- **script.js**: JavaScript file handling the translation logic and interactions.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, etc.)
- An active internet connection to load the Bootstrap CDN.

### Running the Project
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/multilingual-translator.git
    cd multilingual-translator
    ```

2. **Open the Application**:
   - Open `index.html` in a web browser to launch the application.

## Usage
1. Select the **Source Language** (English by default).
2. Choose the **Target Languages** (currently set to translate to Italian, Spanish, French, German, and Portuguese).
3. Enter the text you want to translate in the **Text to Translate** field.
4. Click the **Translate** button to display the translation results in the **Translation Result** section.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Styling**: Bootstrap for responsive design
- **Backend API**: Integration with an external translation API (set up in `script.js`)

## Code Overview
- **HTML Structure**: 
  - A form that includes dropdowns for source and target languages and a text area for input.
  - A `Translate` button triggers the translation.
  - A section to display translation results dynamically.
  
- **JavaScript (`script.js`)**:
  - Handles the API call to fetch translations and displays the result.

## Customization
- Update the `sourceLang` and `targetLang` options in the HTML as needed.
- Customize the styling in `styles.css` to match your design requirements.
- Set up and configure the API endpoint in `script.js` for translation logic.

## License
This project is licensed under the MIT License.

---

Enjoy using the Multilingual Translator!
