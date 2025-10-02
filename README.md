# i18n Translation Editor with AI

A powerful, single-file web application for managing and translating i18n JSON files. Built with vanilla JavaScript and featuring AI-powered translations via Google's Gemini API.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![No Dependencies](https://img.shields.io/badge/dependencies-none-green.svg)

## ✨ Features

- **📁 Multi-file Support** - Load multiple JSON translation files at once
- **📊 Spreadsheet Interface** - Edit translations in a familiar table layout
- **🔄 Resizable Columns** - Adjust column widths for better readability
- **🤖 AI Translation** - Translate entire columns to new languages using Gemini AI
- **💾 Export Ready** - Download updated JSON files with one click
- **🎨 Dark Mode UI** - Easy on the eyes with a modern dark theme
- **⚡ Zero Dependencies** - Pure vanilla JavaScript, no frameworks or libraries
- **🔒 Privacy First** - All processing happens in your browser

## 🚀 Quick Start

1. **Open the app** - Simply open `index.html` in your browser
2. **Upload files** - Drag and drop or select your `.json` translation files
3. **Edit translations** - Click any cell to edit its content
4. **Export** - Download your updated JSON files

## 🤖 AI Translation Setup

To use the AI translation feature:

1. Get a Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Click "Translate with AI"
3. Select source language and enter target language code
4. Enter your API key (stored locally in your browser)
5. Click "Translate"

The app will translate all keys from the source language to the new target language.

## 📋 File Format

Your JSON files should follow this structure:

```json
{
  "welcome_message": "Welcome to our app",
  "login_button": "Log in",
  "signup_button": "Sign up"
}
```

Name your files using language codes (e.g., `en.json`, `es.json`, `fr.json`).

## 🛠️ Technical Details

- **No build process required** - Single HTML file with embedded CSS and JavaScript
- **Local storage** - API key is saved in browser's localStorage for convenience
- **Rate limiting** - Built-in exponential backoff for API calls
- **Error handling** - Graceful error messages and retry logic

## 📝 Usage Example

1. Prepare your translation files:
   ```
   en.json
   es.json
   fr.json
   ```

2. Upload all files to the editor

3. Edit any translations directly in the table

4. Need a new language? Use AI translation:
   - Source: `en`
   - Target: `de`
   - The app creates a complete German translation

5. Export all files including the new `de.json`

## 🔐 Privacy & Security

- Your API key is stored only in your browser's localStorage
- All translation data stays in your browser
- No data is sent to any server except Google's Gemini API for translations
- You can clear your API key anytime by clearing localStorage

## 💡 Tips

- **Batch editing** - Edit multiple translations before exporting
- **Visual feedback** - Updated cells flash green to confirm changes
- **Keyboard navigation** - Tab through cells like a spreadsheet
- **Column resizing** - Hover over column borders and drag to resize

## 👤 Author

**Pietro Suma**

- GitHub: [@suma-pietro](https://github.com/suma-pietro)

## 🙏 Acknowledgments

- Powered by [Google Gemini API](https://ai.google.dev/)
- Built with modern web standards
- Inspired by the need for simple, effective i18n management

---

**Made with ❤️ for developers managing multilingual applications**
