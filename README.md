# Gemini Chatbot

Gemini Chatbot is an interactive AI-powered chat application that utilizes Google's Gemini API to generate intelligent responses to user queries. This chatbot is designed with a sleek UI and supports file uploads for enhanced interaction.

## Features
- **Real-time AI Responses**: Utilizes Google's Gemini API to generate responses.
- **File Upload Support**: Users can upload images, PDFs, TXT, and CSV files for analysis.
- **Theme Toggle**: Switch between light and dark themes.
- **Chat History**: Maintains conversation context for better responses.
- **Quick Suggestions**: Predefined suggestions for easy access.
- **Typing Effect**: Simulates a real-time typing effect for responses.
- **Responsive Design**: Mobile-friendly and fully responsive layout.

## Usage
1. Enter your message in the input field and press enter or click the send button.
2. Upload files if needed by clicking the attachment button.
3. Click on quick suggestion options to auto-fill the input.
4. Toggle themes using the sun/moon icon.
5. Clear chats using the delete button.

## Project Structure
```
├── index.html      # Main HTML structure
├── script.js       # JavaScript logic for chat interactions
├── style.css       # Styling and themes
```

## API Configuration
This chatbot uses Google's Gemini API for generating responses. Make sure to replace the `API_KEY` in `script.js` with your own API key:
```js
const API_KEY = "YOUR_GOOGLE_GEMINI_API_KEY";
```

## Dependencies
- Google Fonts (Material Icons, Poppins)
- Google Gemini API

## Customization
- Modify `style.css` to adjust the chatbot's appearance.
- Edit `script.js` to add more functionalities.
- Update `index.html` for UI changes.
