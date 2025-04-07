# GestuWave_HandWave


GestuWave_HandWave is an AI-based application that enables users to control their computer using hand gestures. By leveraging Google's MediaPipe for gesture recognition and face landmarking, the application interprets hand movements to perform actions such as navigating the cursor, adjusting volume and brightness, and simulating mouse clicks. Additionally, it utilizes facial landmarking to prevent unintended keystrokes by ensuring the user's face is detected.

**Key Features:**

- **Gesture Recognition:** Utilizes MediaPipe's robust hand recognition capabilities to identify various hand gestures, mapping them to custom-defined actions for intuitive input.

- **Cursor Control:** Maps hand movements to cursor movements on the screen, allowing for seamless navigation.

- **Volume and Brightness Adjustment:** Assigns specific gestures to increase or decrease system volume and screen brightness.

- **Face Landmarking:** Employs MediaPipe's Face Mesh to track facial landmarks, ensuring the user's face is detected and preventing unintended keystrokes.

- **Presentation Recording:** Allows users to select windows or applications for interaction and recording, with the ability to save recordings locally.

- **Cross-platform Compatibility:** Built with Electron, the application is deployable on various operating systems, including Windows, macOS, and Linux.

**Technology Stack:**

- **Front-end:** Developed using React, TypeScript, and Vite for a responsive and user-friendly interface.

- **Back-end:** Electron serves as the framework, with Sequelize and SQLite3 managing database interactions, and nut-js handling native system interactions.

**Installation and Setup:**

1. **Clone the Repository:** Download the project files using the command:

   ```bash
   git clone https://github.com/gowthamgspatil/GestuWave_HandWave
   ```


2. **Install Dependencies:** Navigate to the project directory and install the necessary packages:

   ```bash
   npm install
   ```


3. **Start Development Version:** Launch the development environment for testing:

   ```bash
   npm run dev
   ```


4. **Build the Application:** For production builds, use:

   ```bash
   npm build      # Builds for the current operating system
   ```


   ```bash
   npm build-all  # Builds for all supported operating systems (macOS only)
   ```


**Development Environment Setup:**

To set up the development environment:

1. **Clone the Repository:** Use the command:

   ```bash
   git clone https://github.com/gowthamgspatil/GestuWave_HandWave
   ```


2. **Install Dependencies:** Navigate to the project directory and install necessary packages:

   ```bash
   npm install
   ```


3. **Start Development Version:** Launch the development environment:

   ```bash
   npm run dev
   ```


4. **Build the Application:** For production builds:

   ```bash
   npm build      # Builds for the current operating system
   ```


   ```bash
   npm build-all  # Builds for all supported operating systems (macOS only)
   ```


**Development and Contributions:**

Developers interested in contributing can access the project's codebase on GitHub. The repository includes instructions for setting up the development environment, contributing guidelines, and information about the project's authors and contributors.

**Note:** Ensure that your system's camera is properly set up and accessible for the application to function correctly. 
