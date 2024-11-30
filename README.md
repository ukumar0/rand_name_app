# Random Namer App

A simple Flutter application that generates and displays random word pairs using the `english_words` package. The app is built with Flutter's modern development practices, leveraging Material 3 design principles and state management with the `provider` package.

---

## Features

- **Random Word Pair Generator:** Generates unique word pairs every time you press the "Next" button.
- **Modern UI Design:** Implements Material 3 design for a sleek and responsive user experience.
- **State Management:** Uses the `provider` package for efficient state handling and UI updates.
- **Theming:** Custom theme based on a seed color for consistent and vibrant UI.

---

## Screenshots

!["Home_Page"](./assets/Screenshot%202024-12-01%20041624.png)

---

## Installation

To run the app on your local machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ukumar0/rand_name_app.git
   cd rand_name_app
2. **Install Dependencies:** Ensure you have Flutter installed on your system, then run:
   ```bash
   flutter pub get
3. **Run the App:**
   ```bash
   flutter run


**Tech Stack**
- Language: Dart
- Framework: Flutter
- State Management: Provider
- UI Framework: Material 3
- Dependencies:
  - english_words: For generating random word pairs(importing through a dart library)
  - provider: For state management
 

## Code Structure
The app follows a clean and modular architecture:

- **main.dart**: Entry point of the application.
- **MyAppState**: Manages state and notifies listeners of updates.
- **MyHomePage**: Main UI displaying the current word pair and a button for generating the next pair.
<<<<<<< HEAD
- **BigCard**: Custom widget displaying the word pair inside a styled card.
=======
- **BigCard**: Custom widget displaying the word pair inside a styled card.
>>>>>>> 262339fa6ea73fa950d5acc54ef77a67b5bdad89
