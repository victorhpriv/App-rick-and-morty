# Rick and Morty App - Kobe Challenge

This Flutter project implements the required features:
- Scrollable list of characters (name + image)
- Detail screen with: name, image, species, gender, status, origin, last location, first appearance
- Navigation from list to details
- Uses Rick and Morty REST API (https://rickandmortyapi.com/)

## Setup

1. **Install Flutter SDK** and set up your environment: https://docs.flutter.dev/get-started/install
2. **Replace placeholder fonts**:
   - Download Lato fonts from Google Fonts: https://fonts.google.com/specimen/Lato
   - Put the `.ttf` files in `assets/fonts/` (replace the placeholder files included)
3. Run:
```bash
flutter pub get
flutter run -d chrome
```
(or run on emulator/device)

## Project structure

- lib/pages/home_page.dart - list & API integration
- lib/pages/detail_page.dart - detail view (fetches first episode title)
- lib/models/character.dart - Character model
- lib/services/api_service.dart - API calls
- lib/widgets/character_card.dart - UI card used in list

## Notes

- The `assets/fonts` directory contains placeholder files named like `.ttf`. **You MUST replace them** with the real Lato `.ttf` files before running to avoid font errors.
- If you want the app to look exactly like the Figma prototype, tweak colors, paddings and logo assets accordingly. I can help with that.

Good luck — ping me if you want me to create the PR description and README improvements.
