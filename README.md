# Navigation App

## Overview
This project is an Android application built with **Kotlin** and **Jetpack Compose** that demonstrates navigation across three screens using **Navigation Compose** and **Accompanist Navigation Animation**.  

The app flow:
1. **Home Screen** → Input your name.  
2. **Second Screen** → Input two numbers.  
3. **Third Screen** → Display your name and the sum of the two numbers.  

Navigation includes **Next**, **Back**, and **Go Home** buttons to move between screens.

---

## Features
- **Home Screen**  
  - Input your name.  
  - Navigate to the second screen.  
  - Preview tab to show entered name.  

- **Second Screen**  
  - Input two numbers.  
  - Navigate forward to the third screen.  
  - Back button to return to the home screen.  

- **Third Screen**  
  - Displays the user’s name and the sum of the two numbers.  
  - "Go Home" button to return to the home screen.  
  - Back button to return to the second screen.  

- **Navigation Drawer**  
  - Access Home and Page Two directly from the drawer menu.  

---

## Tech Stack
- **Kotlin**  
- **Jetpack Compose**  
- **Navigation Compose (2.7.7)**  
- **Accompanist Navigation Animation (0.33.2-alpha)**  
- **Material3 Components**  


```kotlin
dependencies {
    implementation("androidx.navigation:navigation-compose:2.7.7")
    implementation("com.google.accompanist:accompanist-navigation-animation:0.33.2-alpha")
}


## Example Flow
1. **Home Screen** → Enter name → press **Next**.  
2. **Second Screen** → Enter two numbers → press **Next**.  
3. **Third Screen** → Displays name and sum → press **Go Home** to return.


## Conclusion
This app demonstrates how to implement **multi-screen navigation** in Jetpack Compose using **Navigation Compose** and **Accompanist**. It fulfills the assignment requirements by providing a clean navigation flow with input handling, back navigation, and a drawer menu.
