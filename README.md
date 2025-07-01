# NaVino
NaVino is an innovative Android application designed to enhance your real-world audio experience by intelligently managing sound based on your geographic location. It allows users to define custom "sound-muted zones" on a map. When you enter one of these predefined areas, the application automatically mutes your device's audio, and when you leave the area, the sound is automatically unmuted. This is perfect for ensuring quiet in specific places like libraries, quiet study zones, or during meetings, without manually adjusting your device's volume.

## Table of Contents
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies Used](#technologies-used)
* [Contributing](#contributing)
* [License](#license)

## Features
* **Geofencing:** Define custom polygonal areas on a map where sound should be muted.
* **Location-Aware Audio Control:** Automatically mutes device audio upon entering a defined zone.
* **Automatic Unmute:** Restores device audio when exiting a defined zone.
* **Intuitive Map Interface:** Easily draw and manage your sound-muted areas directly on the map.

## Installation
To get NaVino up and running on your Android device or emulator:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Marianie-Alphonse/NaVino.git](https://github.com/Marianie-Alphonse/NaVino.git)
    ```
2.  **Open in Android Studio:**
    * Launch Android Studio.
    * Select `File` > `Open` and navigate to the cloned `NaVino` directory.
3.  **Build the project:**
    * Android Studio will automatically try to sync the project with Gradle.
    * Ensure you have the necessary Android SDK versions and build tools installed (as specified in `build.gradle`).
4.  **Run on a device/emulator:**
    * Connect an Android device or start an AVD (Android Virtual Device) emulator.
    * Click the `Run` button (green play icon) in Android Studio.

## Usage
1.  **Grant Permissions:** Upon first launch, the app will likely request location permissions. Grant these for the app to function correctly.
2.  **Define Zones:** Use the map interface to draw the boundaries of your desired sound-muted areas.
    * [Further instructions on how to draw/edit areas would go here, e.g., "Tap and hold to start drawing, tap to add points, tap to close shape." - *You'll need to fill in specifics based on your UI.*]
3.  **Activate Zones:** Once a zone is defined, ensure it's active.
4.  **Experience Automatic Muting:** As you physically enter or leave the defined areas, your device's sound will be muted or unmuted accordingly.

## Technologies Used
* **Android SDK:** For core application development.
* **Google Maps API:** For displaying maps and enabling zone drawing.
* **Android Location Services (Geofencing API):** For detecting entry and exit from defined geographic areas.
* **Android Audio Manager:** For controlling device sound.
* **Gradle:** For build automation.

## Contributing
We welcome contributions to NaVino! If you have suggestions for improvements, bug fixes, or new features, please feel free to:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License
[Consider adding a license file to your repository, such as MIT, Apache 2.0, or GPL.]

This project is licensed under the [Your Chosen License Name] - see the `LICENSE` file for details.
