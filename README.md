# Password Generator

A simple password generator built using React that allows users to generate secure passwords with customizable options.

## Features
- Generate a random password
- Adjust password length (6-20 characters)
- Include numbers in the password
- Include special characters in the password
- Copy the generated password to the clipboard

## Technologies Used
- React
- Tailwind CSS
- JavaScript (ES6+)
- Hooks: `useState`, `useEffect`, `useCallback`, `useRef`

## Installation & Usage

### Prerequisites
Make sure you have **Node.js** and **npm** installed on your system.

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-generator.git
   cd password-generator
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Code Explanation
- `useState` is used to manage the state of password length, number inclusion, special characters, and the generated password.
- `useCallback` ensures functions like `passwordGenerator` and `copyPasswordToClipboard` are optimized and don’t get recreated unnecessarily.
- `useEffect` automatically updates the password whenever user preferences change.
- `useRef` is used to reference the password input field for copying functionality.
- Tailwind CSS is used for styling and responsiveness.

## Improvements & Future Enhancements
- Add an option to include lowercase and uppercase separately
- Improve UI with animations and better styling
- Provide a strength indicator for generated passwords
- Save generated passwords to local storage

## License
This project is open-source and available under the [MIT License](LICENSE).

---
Feel free to contribute and improve the project! 🚀

