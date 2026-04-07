# Inventory App

A Flutter inventory management application integrated with Firebase Firestore.

## Features
- Add, update, and delete inventory items
- Real-time item display using StreamBuilder
- Search and filter items
- Highlight low-stock items (quantity ≤ 5)

## Enhanced Features
1. Search functionality for filtering inventory items by name.
2. Low-stock filter and highlighting for quickly identifying items with quantity below 5.
3. Form validation to prevent invalid quantity and price values.
4. Delete confirmation dialog for safer item removal.

## Getting Started

### 1. Install dependencies
```sh
flutter pub add firebase_core cloud_firestore
```

### 2. Configure Firebase
- Install the FlutterFire CLI if you haven't:
  ```sh
  dart pub global activate flutterfire_cli
  ```
- Run the configuration:
  ```sh
  flutterfire configure --platforms=android
  ```
  - Select your Firebase project or create a new one
  - Choose Android only

### 3. Folder Structure
```
lib/
├── main.dart
├── models/
│   └── item_model.dart
├── services/
│   └── firestore_service.dart
├── pages/
│   └── inventory_page.dart
```

## Tech Stack
- Flutter
- Firebase Core
- Cloud Firestore

## Author
Darin