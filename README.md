# Dice Roller App

## Description
The Dice Roller App is a simple Android application developed using Kotlin and Jetpack Compose. It displays a dice image and allows users to roll the dice by clicking the **Roll** button. Each click generates a random number between 1 and 6 and updates the dice image accordingly.

## Aim
To develop an interactive Android application that simulates rolling a dice using Kotlin and Jetpack Compose.

## Features
- Displays a dice image.
- Generates a random number from 1 to 6.
- Updates the dice image whenever the Roll button is clicked.
- Uses a simple and user-friendly interface.
- Provides a preview of the application UI.

## Technologies Used
- **Programming Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Design:** Material 3
- **IDE:** Android Studio

## Application Components
- `MainActivity.kt` – Main entry point of the application.
- `DiceRollerApp()` – Sets up the main application layout.
- `DiceWithButtonAndImage()` – Displays the dice image and Roll button and handles dice rolling.
- `DiceRollerPreview()` – Provides a preview of the application UI.

## How It Works
1. Initially, the application displays dice face 1.
2. The user clicks the **Roll** button.
3. A random number between 1 and 6 is generated.
4. The corresponding dice image is displayed on the screen.
5. The user can click Roll again to roll the dice another time.

## Required Image Resources
Add the following dice images to the `res/drawable` folder:
- `one`
- `two`
- `three`
- `four`
- `five`
- `six`

## How to Run
1. Clone or download the repository.
2. Open the project in Android Studio.
3. Ensure all six dice images are present in the `res/drawable` folder.
4. Sync the Gradle files.
5. Run the application on an Android emulator or physical device.
6. Click **Roll** to generate a random dice result.

## Concepts Learned
- Kotlin variables and state management
- Jetpack Compose `@Composable` functions
- `remember` and `mutableStateOf`
- Random number generation using `(1..6).random()`
- Conditional image selection using `when`
- Layouts using `Column` and `Spacer`
- Handling button click events
- Displaying drawable resources using `painterResource`

## Author
**Kondri Indumathi**

## 📄 License
This project is created for learning and educational purposes.
