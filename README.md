# 24012021096_MAD_Pr8

# Hello World iOS App using SwiftUI

## 📌 Overview

This project is part of **Mobile Application Development – Practical 8**. It demonstrates how to create, build, and run a basic iOS application using **Swift and SwiftUI** in Xcode.

The application displays a simple **"Hello, world!"** message on the screen and introduces the basic structure of a SwiftUI application.

## 🎯 Aim

To create and run your first Hello World iOS application using SwiftUI.

## 🛠️ Technologies Used

- **Programming Language:** Swift
- **User Interface Framework:** SwiftUI
- **IDE:** Xcode
- **Platform:** iOS
- **Testing Environment:** iOS Simulator

## ✨ Features

- Displays a "Hello, world!" message.
- Uses SwiftUI to build the user interface.
- Demonstrates the basic structure of an iOS application.
- Supports live previews through Xcode.
- Runs on an iOS Simulator without requiring a physical iPhone.

## 📂 Project Structure

A typical Xcode project for this practical contains the following files:

```text
HelloWorld/
├── HelloWorldApp.swift
├── ContentView.swift
├── Assets.xcassets/
└── Preview Content/
```

- **HelloWorldApp.swift:** Defines the app's entry point and main scene.
- **ContentView.swift:** Defines the main user interface.
- **Assets.xcassets:** Stores app images, icons, and other visual assets.
- **Preview Content:** Contains resources used for previews, if included.

*Note: The exact filenames and folders may vary depending on the project name and Xcode version.*

## 💻 Source Code

### 1. App Entry Point

The app entry-point file initializes the SwiftUI application and displays `ContentView`.

```swift
import SwiftUI

@main
struct HelloWorldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

### 2. ContentView.swift

This file defines the main screen and displays the greeting.

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}

#Preview {
    ContentView()
}
```

## 🚀 How to Run the Project

1. Install Xcode on a Mac.
2. Open Xcode and select **File → New → Project**.
3. Select the **iOS App** template.
4. Enter `HelloWorld` as the product name.
5. Select **SwiftUI** as the interface and **Swift** as the language.
6. Create the project and open it in Xcode.
7. Add or replace the code in the appropriate Swift files.
8. Select an available iOS Simulator from the device menu.
9. Click the **Run ▶** button to build and launch the application.
10. View the output in the simulator.

## 📱 Expected Output

The application displays the following message in the center area of a simple iOS screen:

**Hello, world!**

The app can also be previewed directly in Xcode using the SwiftUI preview canvas.

## 📚 Concepts Learned

- Creating a new iOS application in Xcode.
- Understanding the structure of a SwiftUI project.
- Using the `App` protocol and `WindowGroup`.
- Creating a user interface with the `View` protocol.
- Displaying text using the `Text` view.
- Applying layout modifiers such as `.padding()`.
- Running an application in the iOS Simulator.
- Previewing UI changes using SwiftUI previews.
- Initializing a Git repository for version control.

## 🔧 Requirements

- A Mac running a version of macOS compatible with Xcode.
- Xcode with an iOS SDK and Simulator.
- Basic knowledge of Swift programming.

## 👨‍💻 Author

**Naimish Bhadrecha**

Department of Information Technology

Mobile Application Development – Practical 8

## 📄 License

This project was created for educational and academic purposes. No specific open-source license has been assigned.
