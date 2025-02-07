
# Puff Chatbot Application

A custom chatbot application built in Flutter using Dash Chat, powered by Google's Gemini AI for intelligent conversation processing.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Steps to Install](#steps-to-install)
- [Usage](#usage)
- [Configuration](#configuration)
- [Limitations & Future Scope](#limitations--future-scope)
  - [Current Limitations](#current-limitations)
  - [Future Enhancements](#future-enhancements)
- [Contribution](#contribution)
- [License](#license)
- [References](#references)
- [Contributors](#contributors)
- [Support & Star](#support--star)


## Features
- **Real-time Chat** – Engages users with AI-generated responses.
- **Context Awareness** – Understands user inputs for meaningful conversations.
- **Lightweight & Fast** – Optimized for smooth performance.

## Technologies Used
- **Flutter** – For building a cross-platform mobile application.
- **Dash Chat** – For implementing the interactive chat interface.
- **Gemini AI** – For natural language processing and response generation.

## Installation

### Prerequisites
- Install Flutter: [Flutter Setup](https://flutter.dev/docs/get-started/install)
- Ensure you have Dart SDK installed.
- Obtain a Gemini AI API key from [Google AI](https://ai.google.dev/).

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/aavvvacado/Puff-Chatbot.git
   cd Puff-Chatbot
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Configure the Gemini AI API key in your environment variables or within the project’s configuration file.
4. Run the application:
   ```bash
   flutter run
   ```

## Usage
- Open the app and start a conversation with the chatbot.
- The chatbot processes inputs using Gemini AI and provides intelligent responses.
- Customize the chat UI via Dash Chat settings.

## Configuration
In lib/constants/api_constants.dart paste your api key
```
const String GEMINI_API_KEY = "your_api_key_here";
```

## Limitations & Future Scope
### Current Limitations
- Response latency depends on API calls.
- Limited offline functionality.
- answers to new questions only
- not much efficient with images

### Future Enhancements
- Multi-language support.
- Enhanced AI personalization.
- Voice assistant integration.
- chat storage for future 
  

## Contribution
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push the branch: `git push origin feature-branch`.
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## References
- [Flutter Documentation](https://flutter.dev/docs)
- [Dash Chat Package](https://pub.dev/packages/dash_chat)
- [Gemini AI API](https://ai.google.dev/)

## Contributors
- **Owner:** [aavvvacado](https://github.com/aavvvacado)

## Support & Star
If you found this project useful, please consider giving it a ⭐ on GitHub!
