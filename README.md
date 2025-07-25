# Voice Based Email System (For Blinds)

An Android application designed to help visually impaired individuals send and receive emails using voice commands, making digital communication more accessible and inclusive.

## 📋 Table of Contents
- [About](#about)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Architecture](#architecture)
- [Testing](#testing)
- [Limitations](#limitations)
- [Future Scope](#future-scope)
- [Team](#team)
- [License](#license)

## 🎯 About

The Voice Based Email System is an innovative Android application developed as part of a Bachelor of Computer Application project at International Institute of Professional Studies, DAVV, Indore. This system addresses the digital divide faced by visually impaired individuals by providing a completely voice-controlled email interface.

The application eliminates the need for traditional keyboard input and visual interfaces, instead relying on speech-to-text and text-to-speech technologies to create an accessible email experience.

## ✨ Features

- **Voice-Controlled Interface**: Complete email composition using voice commands
- **Speech-to-Text Conversion**: Converts spoken words into text for email content
- **Text-to-Speech Feedback**: Provides audio feedback for all system interactions
- **Interactive Voice Prompts**: Guides users through the email composition process
- **Gmail Integration**: Seamlessly sends emails through Gmail accounts
- **User-Friendly Commands**: Simple voice commands for To, Subject, Message, Send, and Cancel operations
- **Accessibility First**: Designed specifically for visually impaired users
- **No Visual Interface Required**: Completely audio-based interaction

## 🛠 Technology Stack

- **Programming Language**: Java 1.8
- **Development Environment**: Android Studio
- **Platform**: Android 4.4 and above
- **Frontend**: Android XML, Java
- **APIs Used**:
  - Java Speech API
  - JavaMail API
  - Android Speech Recognition API
- **Architecture**: Modular approach with separate modules for speech processing and email handling

## 💻 System Requirements

### Hardware Requirements
- **System**: Pentium IV 2.4 GHz or higher
- **RAM**: 512 MB minimum
- **Storage**: 40 GB available space
- **Mobile Device**: Android smartphone with microphone

### Software Requirements
- **Operating System**: Windows 10 or above (for development)
- **Android Version**: 4.4 (API level 19) or higher
- **Development IDE**: Android Studio
- **Java Version**: 1.8 or higher

## 📱 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/voice-based-email-system.git
   cd voice-based-email-system
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing Android Studio project"
   - Navigate to the cloned repository folder

3. **Configure Dependencies**
   - Ensure all required dependencies are installed
   - Sync the project with Gradle files

4. **Build and Run**
   - Connect an Android device or start an emulator
   - Click "Run" or use `Ctrl+R` to build and install the app

## 🎙 Usage

1. **Launch the Application**
   - Open the VoiceMail app on your Android device
   - The app will greet you with a welcome message

2. **Compose an Email**
   - Tap anywhere on the screen to start
   - Follow the voice prompts:
     - Speak the recipient's email address when prompted
     - Provide the email subject
     - Dictate your message content
     - Confirm to send or cancel the email

3. **Voice Commands**
   - **"To"**: Specify recipient email address
   - **"Subject"**: Set email subject line
   - **"Message"**: Dictate email content
   - **"Send"**: Send the composed email
   - **"Cancel"**: Cancel the current operation

## 🏗 Architecture

The system follows a modular architecture with three main components:

1. **Speech-to-Text Module**: Converts voice input to text using Android's speech recognition
2. **Text-to-Speech Module**: Provides audio feedback using Java Speech API
3. **Email Module**: Handles email composition and sending via JavaMail API

### Key Algorithms
- **HMM (Hidden Markov Model)**: Used for voice recognition processing
- **Speech Recognition**: Powered by Google's speech recognition services

## 🧪 Testing

The application has been thoroughly tested with:
- **Unit Testing**: Individual component functionality
- **System Testing**: End-to-end email sending process
- **Acceptance Testing**: User experience validation
- **Multiple Email Accounts**: Tested with various Gmail accounts

### Test Results
- Successfully tested with 5+ different email accounts
- Voice recognition accuracy: High for clear speech input
- Email delivery: 100% success rate in test cases

## ⚠ Limitations

- **Speech Dependency**: Requires users to be able to speak clearly
- **Gmail Only**: Currently supports only Gmail accounts
- **Internet Required**: Needs active internet connection
- **Security Considerations**: Voice input may compromise privacy in public spaces
- **Send Only**: Currently supports sending emails but not reading received emails
- **Language Support**: Optimized for English language input

## 🚀 Future Scope

- **Multi-Platform Support**: Extend to iOS and web platforms
- **Multiple Email Providers**: Support for Yahoo, Outlook, and other email services
- **Biometric Authentication**: Enhanced security features
- **Email Reading**: Voice-based email reading functionality
- **Multi-Language Support**: Support for regional Indian languages
- **Attachment Support**: Voice-controlled file attachments
- **Advanced Voice Commands**: More sophisticated command recognition
- **Offline Capabilities**: Basic functionality without internet

## 👥 Team

This project was developed by a team of dedicated BCA students:

- **Prakhar Khandelwal** (IC-2K20-53)
- **Prakshep Goswami** (IC-2K20-54)  
- **Pranjali Mishra** (IC-2K20-55)
- **Pratham Jaiswal** (IC-2K20-58)

**Academic Session**: January – June 2023  
**Institution**: International Institute of Professional Studies, Devi Ahilya Vishwavidyalaya, Indore

## 📄 License

This project was developed as an academic project for educational purposes. Please contact the team members for any usage permissions or collaborations.

---

## 🤝 Contributing

While this was an academic project, we welcome suggestions and improvements. Feel free to:
- Report bugs or issues
- Suggest new features
- Contribute to documentation
- Share feedback on accessibility improvements

## 📞 Contact

For any queries or collaborations, please reach out to the development team through the institution or create an issue in this repository.

---

**Note**: This project represents our commitment to creating inclusive technology that bridges the digital divide and empowers visually impaired individuals to participate fully in the digital world.
```


