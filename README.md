# Password Strength Checker & Generator

## Overview
This is a lightweight, browser-based tool that helps users create and evaluate password strength. It combines two essential password security features:
1. A comprehensive password strength checker that evaluates passwords against common security criteria
2. A customizable random password generator that creates strong, unique passwords

## Features

### Password Strength Checker
- **Real-time strength evaluation** with visual feedback
- **Color-coded strength meter** that changes based on password security level
- **Specific feedback** about password strength and suggestions for improvement
- **Multiple security criteria checks:**
  - Minimum length (8 characters)
  - Presence of uppercase letters
  - Presence of lowercase letters
  - Inclusion of numbers
  - Use of special characters
  - Not a common/weak password

### Password Generator
- **Customizable password creation** with options for:
  - Password length (8-64 characters)
  - Character types (uppercase, lowercase, numbers, special characters)
- **Enhanced security features:**
  - Exclusion of similar-looking characters to prevent confusion
  - Guaranteed inclusion of at least one character from each selected type
  - Random shuffling to prevent predictable patterns
- **Convenience functions:**
  - One-click password generation
  - Copy to clipboard functionality
  - Visual confirmation when password is copied

## How to Use

### Installation
1. Download all files to your local machine
2. Open the HTML file in any modern web browser
3. No internet connection required - works completely offline

### Using the Strength Checker
1. Enter a password in the input field
2. View real-time feedback on the strength meter
3. Check which security criteria are being met (green dots) or failed (gray dots)
4. Read the specific feedback message for improvement suggestions

### Using the Password Generator
1. Select your preferred password options:
   - Check/uncheck the character types you want to include
   - Set your desired password length using the number input
2. Click "Generate Password" to create a new password
3. The generated password will appear in the input field and be automatically checked for strength
4. Click "Copy to Clipboard" to copy the password for use elsewhere

## Security Notes
- This tool operates entirely in your browser - passwords are never transmitted over the internet
- The strength checker uses industry-standard criteria but cannot guarantee absolute security
- Even "Very Strong" passwords should be used as part of a broader security strategy:
  - Use unique passwords for different services
  - Consider a password manager for secure storage
  - Enable two-factor authentication when available

## Technical Details
- Built with vanilla HTML, CSS, and JavaScript
- No external libraries or dependencies
- Compatible with all modern browsers
- Responsive design works on desktop and mobile devices

## Development
Want to modify or extend this tool?
- The code is fully commented for easy understanding
- The modular structure allows for simple feature additions
- You can easily customize:
  - The common password detection list
  - The strength calculation algorithm
  - The visual design through CSS

## License
This tool is provided under the MIT License. Feel free to use, modify, and distribute as needed.
