# Smart Email Assistant

An AI-powered browser extension that automates email replies within Gmail, enhancing productivity and personalization.

## Features

- **AI-Generated Responses:** Automatically generate email replies using advanced AI algorithms.
- **Tone Customization:** Choose from various tones (e.g., Professional, Friendly) to match your communication style.
- **Seamless Integration:** Injects an "AI Reply" button into Gmail's toolbar for easy access.
- **Clipboard Functionality:** Automatically pastes the generated reply into the message box upon selection.

## Technologies Used

- **Backend:** Spring Boot 3  
- **AI Integration:** Gemini AI  
- **Frontend:** Angular with Bootstrap  
- **Authentication:** JWT Tokens  

## Installation

1. **Clone the Repository:** Run `git clone https://github.com/yourusername/smart-email-assistant.git` to download the project locally.  
2. **Navigate to the Project Directory:** Move into the project folder using `cd smart-email-assistant`.  
3. **Install Dependencies:** Execute `npm install` to install all necessary dependencies.  
4. **Build the Extension:** Run `npm run build` to create the production-ready build.  
5. **Load the Extension in Chrome:** Open `chrome://extensions/`, enable "Developer mode," click "Load unpacked," and select the `dist` directory.  
6. **Load the Extension in Firefox:** Open `about:debugging`, click "This Firefox," then "Load Temporary Add-on," and select the `manifest.json` file in the `dist` directory.  

## Usage

1. **Open Gmail:** Ensure you’re logged into your Gmail account.  
2. **Compose or Reply to an Email:** Click the "Compose" button or open an email thread.  
3. **Generate a Reply:** Click the "AI Reply" button in the toolbar.  
4. **Select a Tone:** Choose a reply tone such as Professional, Friendly, or Neutral.  
5. **Insert Reply:** The AI-generated response will be automatically pasted into the message box.  

## Contributing

1. **Fork the Repository:** Click the "Fork" button at the top right of this page.  
2. **Clone Your Fork:** Run `git clone https://github.com/yourusername/smart-email-assistant.git`.  
3. **Create a New Branch:** Use `git checkout -b feature/your-feature-name` to start working on a new feature.  
4. **Make Changes and Commit:** Stage changes with `git add .`, commit them using `git commit -m "Add your commit message"`.  
5. **Push to Your Fork:** Run `git push origin feature/your-feature-name`.  
6. **Create a Pull Request:** Navigate to the original repository and click "New Pull Request."  

## License

Distributed under the MIT License. See `LICENSE` for more details.  

## Acknowledgments  

- **Spring Boot:** For building the robust backend.  
- **Gemini AI:** For providing advanced AI capabilities.  
- **Angular & Bootstrap:** For creating a responsive and user-friendly interface.  
- **JWT:** For secure authentication.  
