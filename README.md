
# Hi, I'm Narapureddy Durga Prasad Reddy! 👋

AlgoMentor is a Chrome extension that integrates with maang.in, providing users with an AI-powered coding assistant directly within their problem-solving environment. The extension leverages Google's Gemini API to help debug code, optimize solutions, and understand problem requirements better.
# AlgoMentor

## Features -

## 🤖 AI-Powered Assistance

* Contextual Problem Analysis: Automatically extracts problem title, description, 
requirements, and sample input/output.
* Code-Aware Responses: Analyzes your current code in the editor to provide relevant 
feedback and suggestions.
* Step-by-Step Explanations: Breaks down complex problems and explains solutions in a 
clear, educational manner.

## 💬 Interactive Chat Interface

* Dedicated Chat Overlay: Clean, non-intrusive chat interface that appears when needed.

* Conversation History: Maintains conversation history per problem, even between sessions.

* Clear Conversations: Option to clear chat history when you want to start fresh.

* Helpful Command Recognition: Special commands to retrieve your current code or review 
  previous questions.

## 🔑 API Key Management

* Secure Key Storage: Safely stores your Gemini API key in Chrome's local storage.

* User-Friendly Interface: Simple popup to manage your API key with edit and save 
  functionality.

* Validation Feedback: Clear status messages about API key operations.


## 🛠️ Technical Features

* Persistent Storage: Remembers your settings and conversations between visits.

* Lightweight Design: Minimally impacts browser performance.

* Error Handling: Graceful handling of API errors and connectivity issues.

* Visual Feedback: Tooltips and status indicators for better user experience.

   
## Installation

### Manual Installation (Developer Mode)

    1. Clone this repository or download and extract the ZIP file

```bash
         git clone https://github.com/yourusername/AlgoMentor.git
```
        
    2. Open Chrome and navigate to - chrome://extensions/

    3. Enable "Developer mode" using the toggle in the top-right corner
    4. Click "Load unpacked" and select the extension directory
    5. The extension should now appear in your extensions list and be active

## Setting Up Your API Key
* Get your API key from the [Google AI Studio](https://ai.google.dev/)

* Click on the AlgoMentor extension icon in your Chrome toolbar

* Click the "Edit" button to enable editing of the API Key field

* Enter your Gemini API key

* Click "Save" to store your key

* You'll see a confirmation message "API Key saved successfully!"

## Using AlgoMentor

* Navigate to a problem page on maang.in

* Look for the AlgoMentor icon next to the "Ask Doubt" button

Hover over the icon to see the "Debug Bot" tooltip

* Click on the icon to open the chat interface

* Type your question about the problem or your code

* Receive AI-generated assistance based on the problem context and your code


## Special Commands

* Ask "What is the code that I have written?" to get the current code from your editor

* Ask "What is the first question I asked?" to recall your first non-greeting question

* Type common greetings like "hi" or "hello" for friendly responses


## Troubleshooting

* No Answer Received: If you see "No answer received" as a response, your API key may be incorrect or expired. Try updating it through the popup.

* Error Communicating with Gemini API: Check your internet connection and verify your API key is valid.

* Extension Not Working: Ensure you're on a problem page at maang.in and the site structure hasn't changed.

## Privacy & Data

#### AlgoMentor stores: 

* Your Gemini API key in Chrome's local storage (only on your device)

* Conversation history for each problem (stored locally)

* Current code from the editor when making requests

No data is sent to any servers other than Google's Gemini API for processing queries.

## Technical Details

* Built with JavaScript, HTML, and CSS

* Uses Chrome Extension Manifest V3

* Communicates with Google's Gemini API for AI responses

* Stores data in Chrome's local storage and browser localStorage

## Development
The extension consists of:

* manifest.json: Extension configuration

* popup.html/css/js: API key management interface

* content.js: Problem page integration and chat UI

* background.js: Handles API communication with Gemini

* assets/: Contains images and icons

## Credits
Developed by Narapureddy Durga Prasad Reddy

## Feedback and Contributions
Feedback and contributions are welcome! Please feel free to submit issues or pull requests to improve AlgoMentor.