# mini-project
# BMI Calculator App

## Overview
This app calculates BMI from user height and weight, supporting multiple units. Built in Java (Android) and Flutter (cross-platform).

## Features
- Input validation and unit conversion.
- BMI categories: Underweight, Normal, Overweight, Obese.
- Reset functionality.
- Persistent storage using SharedPreferences.

## Setup
### Flutter
1. Install Flutter SDK.
2. Run `flutter pub get`.
3. Run `flutter run` on Android/iOS.

### Android (Java)
1. Install Android Studio.
2. Open project, build and run on device/emulator.

## Testing
- Functional: Verify calculations (e.g., 170cm/65kg = 22.5 Normal).
- UI: Test on different screens.
- Validation: Check errors for invalid inputs.
- Cross-Platform: Run Flutter on Android/iOS.

## UML Diagrams
- Use Case: User enters data → Calculates → Views result.
- Activity: Input → Validate → Compute → Display.
- Class: MainActivity/BMICalculator (Java); BMICalculatorPage (Flutter).
