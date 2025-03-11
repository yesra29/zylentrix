 API Fetch - Flutter

 Overview
This Flutter project fetches and displays posts from an API using the `http` package. The app supports both light and dark themes, which can be toggled by the user.

 Features
- Fetches posts from [JSONPlaceholder API](https://jsonplaceholder.typicode.com/posts)
- Displays posts in a list view
- Dark mode and light mode support
- Theme toggle functionality

 Installation
 Prerequisites
Ensure you have the following installed:
- Flutter SDK ([Download here](https://flutter.dev/docs/get-started/install))
- Dart
- Git (for version control, optional)

 Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**
   ```sh
   flutter pub get
   ```

3. **Run the App**
   ```sh
   flutter run
   ```

 Project Structure

https://github.com/user-attachments/assets/91c79277-be96-4723-87d9-1c27adc71748


```
lib/
├── main.dart                 # Entry point of the application
├── post_screen/
│   ├── post_screen.dart      # UI and logic for displaying posts
```

 Dependencies
This project uses the following dependencies:
- `flutter`: Flutter framework
- `http`: For making network requests

To install dependencies manually, run:
```sh
flutter pub add http
```

 API Used
The app fetches posts from:
```
https://jsonplaceholder.typicode.com/posts
```



