# A.I Summarizer Extension

An easy-to-use browser extension that leverages artificial intelligence to summarize web page content instantly.

## Features

- Summarize any web page content with a single click
- Clean and simple popup interface
- Customizable options and settings

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/vaibhavpathak46/ai-summarizer-extension.git
   ```
2. **Load the extension in your browser:**
   - Open your browser's Extensions page
   - Click "Load unpacked" (in Chrome: chrome://extensions/)
   - Select the project folder you just cloned

## How to Use

1. Click the A.I Summarizer icon in your browser toolbar.
2. In the popup, click the **Summarize** button to generate a summary of the current web page.
3. The summary will appear in the popup window.
4. To adjust settings or enter your API key, right-click the extension icon and select **Options**.

## API Key Setup (Gemini)

To use the summarization feature, you need a Gemini API key from Google AI:

1. Go to the [Google AI Gemini API page](https://aistudio.google.com/app/apikey).
2. Sign in with your Google account and generate a new API key.
3. Copy the API key provided.
4. Open the extension's options page:
   - Right-click the extension icon and select **Options**
   - Paste your Gemini API key into the provided field and save
5. Your API key will be securely stored in your browser and used for summarization requests.

**Note:** Never share your API key publicly. If you believe your key has been compromised, revoke it and generate a new one from the Gemini dashboard.

## Project Structure

- `background.js` — Handles background tasks and extension logic
- `content.js` — Injects scripts and interacts with web pages
- `popup.html` & `popup.js` — User interface for the extension
- `options.html` & `options.js` — Settings and customization
- `manifest.json` — Extension configuration
- `icon.png` — Extension icon
