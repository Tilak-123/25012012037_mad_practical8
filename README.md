# Hello World iOS App (Practical 8)

## Student Information
* **Name:** Dhruvil Gandhi[cite: 1]
* **Enrollment Number:** 25012012005[cite: 1]
* **Batch:** CE-H-1[cite: 1]

---

## Aim
Create your first Hello World iOS app in SwiftUI[cite: 1].

---

## Project Overview
This project is a basic iOS application built using Xcode, SwiftUI, and the Swift programming language[cite: 1, 2]. It serves as an introductory guide to setting up an iOS project, understanding its core file structure, running the app on a simulator, and utilizing live SwiftUI previews[cite: 1, 3, 4, 5].

---

## Step-by-Step Implementation Guide

### 1. Creating a New Project in Xcode
* Open Xcode and navigate to **File -> New -> Project...**[cite: 1]
* Select the **App** template from the **Application** section under the **iOS** tab[cite: 1].
* Configure the project options as follows:
  * **Product Name:** `hello world`[cite: 2]
  * **Team:** None[cite: 2]
  * **Organization Identifier:** `apprentice`[cite: 2]
  * **Bundle Identifier:** `apprentice.hello-world`[cite: 2]
  * **Interface:** SwiftUI[cite: 2]
  * **Language:** Swift[cite: 2]
  * **Core Data & Unit Tests:** Ensure both options remain unchecked (deselected) as they are not needed for a basic app[cite: 1, 2].
* Check **Create Git repository on my Mac** to initialize version control, then save the project[cite: 2].

### 2. Understanding Project File Structure
The project contains two primary source code files in the project navigator[cite: 3]:
* **`hello_worldApp.swift`**: Defines the main entry point and structure of the app using the `@main` attribute[cite: 3]. It utilizes a custom structure conforming to the `App` protocol to handle the app's window group and view hierarchy[cite: 3].
* **`ContentView.swift`**: Contains the primary user interface code using a structure conforming to the `View` protocol, displaying the default `Text("Hello, world!")` view with padding[cite: 3].

### 3. Running and Previewing the App
* **Using the iOS Simulator:**
  * Select a target simulator (e.g., iPhone 13) from the dropdown menu at the top of the Xcode window[cite: 4, 5].
  * Click the **Play** (run) button in the top-left corner to build and launch the application in the simulator[cite: 5].
* **Using SwiftUI Previews:**
  * Switch to the `ContentView.swift` file to view the live preview canvas[cite: 5].
  * Click the **Resume** button in the preview window to synchronize changes instantly between code and layout[cite: 5].
