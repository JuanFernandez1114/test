# 📌 Task Squirrel

Task Squirrel is an iOS app that lets you manage tasks, attach photos to
mark them as complete, and view task locations on an interactive map. It
combines productivity with location awareness, making it easy to track
where and how tasks are completed.

------------------------------------------------------------------------

## 🚀 Features

-   ✅ Create and view detailed tasks (title, description, status)\
-   📷 Attach photos from your photo library to complete tasks\
-   🗺️ View completed tasks on a map with custom annotation views\
-   🔒 Handles photo library permission requests\
-   🌙 Adaptive UI with support for light & dark mode

------------------------------------------------------------------------

## 📂 Project Structure

-   **`TaskDetailViewController.swift`**\
    Handles the UI and logic for viewing a task, attaching photos, and
    displaying map locations.

-   **`TaskAnnotationView.swift`**\
    Custom `MKAnnotationView` for displaying task images as pins on the
    map.

-   **`PhotoViewController.swift`**\
    Simple controller to view a task's attached photo in full size.

------------------------------------------------------------------------

## 🛠️ Requirements

-   iOS 15.0+\
-   Xcode 14+\
-   Swift 5.7+

------------------------------------------------------------------------

## 📖 Usage

1.  Clone the repository:

    ``` bash
    git clone https://github.com/your-username/task-squirrel.git
    ```

2.  Open `task-squirrel.xcodeproj` in Xcode.\

3.  Build & run the project on a simulator or physical device.

------------------------------------------------------------------------

## 🔐 Permissions

This app requires **Photo Library Access** in order to attach images to
tasks. If access is denied, the app will prompt you to update your
settings.

------------------------------------------------------------------------

## 📸 Demo GIF

<p align="center">
  <img src="lab1juan.gif" alt="Lab 1 Demo" width="300"/>
</p>



------------------------------------------------------------------------


