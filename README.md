# PlatTrackApp – RAWG Game Tracker

## Description
A SwiftUI app that fetches video game data from the RAWG API and displays it in a dynamic list with images, detail views, and a player profile.

---

## API Used
RAWG Video Games Database API  
https://api.rawg.io

---

## Features
- Fetches live game data using async/await
- Displays games with AsyncImage
- Tap into detailed game view
- Loading and error states
- Pull-to-refresh support
- Add and delete local games
- Player profile stats (total games + platinums)

---

## Architecture
- MVVM (Model-View-ViewModel)
- APIService handles networking
- Codable used for JSON parsing
- @MainActor ViewModel for UI safety

---

## Screenshots
See `/Screenshots` folder for:
- Loading state
- Game list view
- Detail view
- Profile screen

---

## How to Run
1. Clone repo
2. Open in Xcode
3. Run on simulator or device
