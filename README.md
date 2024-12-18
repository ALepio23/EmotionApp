# Emotion Recognition App

An accessible application designed to recognize emotions through text input or speech.
## Features

- **Emotion Recognition**: Analyze emotions based on text input or spoken words.
- **Speech Interaction**: Users can interact with the app by tapping anywhere on the screen to activate or deactivate speech recognition.
- **Accessibility**: The app is designed with accessibility in mind, including VoiceOver support.

## Technologies Used

- **SwiftUI**: For building the user interface.
- **CoreML**: For emotion analysis using machine learning.
- **AVSpeechSynthesizer**: For providing audible feedback to users.
- **SpeechRecognizer**: For handling voice input.

## How to Use

1. **Text Input**:
   - Enter your emotion in the text field.
   - Tap the "Send Text" button to analyze the input.
2. **Speech Recognition**:
   - Tap anywhere on the screen (except for the text field and "Send Text" button) to activate speech recognition.
   - Tap again to deactivate and confirm the input.
3. **Results**:
   - The app will display the recognized emotion in a modal after confirmation.

## Requirements

- **iOS 15.0** or later
- **Xcode 13.0** or later

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/emotion-recognition-app.git
