# scan-mart-frontend

A Flutter application for Scan Mart with login, signup, and dashboard functionality.

## Features

- **Login Screen**: Mobile/Email and Password authentication
- **Signup Screen**: Username, Mobile, Email, and Password registration
- **Dashboard Screen**: Main dashboard with quick actions and statistics
- **Reusable Components**: Custom text fields and buttons
- **Color Constants**: Centralized color management

## Project Structure

```
lib/
├── constants/
│   └── colors.dart          # App color constants
├── widgets/
│   ├── custom_button.dart   # Reusable button widget
│   └── custom_text_field.dart # Reusable text field widget
├── screens/
│   ├── login_screen.dart    # Login screen
│   ├── signup_screen.dart   # Signup screen
│   └── dashboard_screen.dart # Dashboard screen
└── main.dart                # App entry point
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run the app:
   ```bash
   flutter run
   ```

## Dependencies

- Flutter SDK
- cupertino_icons

## Screens

### Login Screen
- Mobile Number or Email input
- Password input with visibility toggle
- Navigation to signup screen
- Forgot password link

### Signup Screen
- Username input
- Mobile number input (10 digits)
- Email input
- Password input with visibility toggle
- Form validation for all fields

### Dashboard Screen
- Welcome card
- Statistics cards
- Quick action buttons
- Logout functionality
