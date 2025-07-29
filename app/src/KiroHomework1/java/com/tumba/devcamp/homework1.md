# 🧭 Jetpack Compose Navigation Homework

This assignment will help you understand how to implement basic navigation in a Jetpack Compose app.
You will create a simple app with three screens and navigate between them using Jetpack Navigation for Compose.

---

## 🎯 Objective

Build a Compose-based Android app with:

- Three composable screens
- Navigation using `NavHost` and `NavController`
- Argument passing between screens

---

## 📱 Screens Overview

### 🏠 HomeScreen
- Displays a welcome message
- Contains a button to navigate to `DetailScreen` with a sample name (e.g., `"John"`)

### 📄 DetailScreen
- Reads and displays the `name` argument passed from `HomeScreen`
- Contains a button to navigate to `SettingsScreen`

### ⚙️ SettingsScreen
- Displays static settings text or placeholders

---

## 🛠 Requirements

- Set up Jetpack Compose Navigation dependencies
- Use `NavController` and `NavHost` to handle navigation
- Define and navigate between routes using `composable()`
- Pass an argument (`name`) from `HomeScreen` to `DetailScreen`

---

## 📦 Bonus Tasks (Optional)

- Add a back button to each screen

---

## 📁 Suggested Project Structure

.
├── MainActivity.kt
├── nav/
│ └── NavGraph.kt
└── ui/screens/
├── HomeScreen.kt
├── DetailScreen.kt
└── SettingsScreen.kt

## 📚 References

- Jetpack Compose Navigation Docs https://developer.android.com/develop/ui/compose/navigation