#French Teacher App

A fun and beginner-friendly Android app designed to help users learn basic French color vocabulary through sound interaction. Tap a color button to instantly hear its pronunciation in French. Built using Java and Android's `MediaPlayer`, this app is perfect for learners and developers alike.

## 🎯 Features

- 🎨 5 colorful buttons: Red, Black, Green, Purple, Yellow
- 🔊 Plays audio pronunciation when a button is tapped
- 🖼️ Themed background image for visual appeal
- ☕ Clean Java code with centralized `OnClickListener` logic
- 🔁 Reusable `PlaySounds()` method to handle audio playback

## 🖌️ UI Design

- **ConstraintLayout** for responsive design
- App title (`TextView`) at the top center
- Vertically stacked `Button` elements for each color
- Buttons are styled with corresponding color text
- Background wallpaper image for engaging presentation

## 🧠 How It Works

- Each button is initialized via `findViewById()` in `MainActivity`
- All buttons share a common `OnClickListener`
- The app uses `MediaPlayer` to play short `.mp3` audio clips stored in `/res/raw`
- Buttons trigger the appropriate French word based on their ID



