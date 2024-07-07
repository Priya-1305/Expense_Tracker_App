# Flutter Expense Tracker App

A simple expense tracker app built with Flutter to help manage daily finances. The app allows users to add, view, and delete expenses, categorized by different types.

## Features

- Add new expenses with title, amount, date, and category.
- View a list of all added expenses.
- Delete expenses with a swipe action.
- Undo expense deletion via Snackbar.
- View expenses summarized in a chart by category.

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/flutter-expense-tracker.git
    cd flutter-expense-tracker
    ```

2. **Install dependencies:**

    ```sh
    flutter pub get
    ```

3. **Run the app:**

    ```sh
    flutter run
    ```

## Project Structure

```sh
lib/
├── main.dart
├── expense.dart
├── expense_item.dart
├── expense_list.dart
├── expns.dart
└── new_expense.dart
