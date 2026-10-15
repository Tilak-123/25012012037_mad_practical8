# Practical 8: First "Hello World" App

## Overview
This repository contains the implementation for **Practical 8** of the Mobile Application Development (MAD) lab curriculum. The objective of this practical is to create, configure, understand, and run a baseline "Hello World" iOS application using **SwiftUI** and **Xcode**[cite: 1, 4].

---

## Aim
To create your first "Hello World" iOS application using SwiftUI.

---

## Project Specifications

| Attribute | Value |
| :--- | :--- |
| **Product Name** | `hello world` |
| **Interface** | SwiftUI[cite: 2] |
| **Language** | Swift[cite: 2] |
| **Organization Identifier** | `apprentice`[cite: 2] |
| **Bundle Identifier** | `apprentice.hello-world`[cite: 2] |
| **Target Device / Simulator** | iPhone 13 (iOS 15.4+) |
| **Version Control** | Git initialized locally[cite: 2] |

---

## File Structure & Code Explanation

### 1. `hello_worldApp.swift`
Defines the main entry point and lifecycle of the application. It utilizes the `@main` attribute and declares the primary app scene wrapped in a `WindowGroup`:

```swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
