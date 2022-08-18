# Faciaro
An app that recommends music based on facial emotions

# Description
Research has shown that listening to music can reduce anxiety, blood pressure, and pain as well as improve sleep quality, mood, mental alertness, and memory. In this fast moving world, it’s difficult to navigate through an app to search for new music. The world awaits a compact solution that provides immediate suggestion of music.

## How Faciaro works

- Picture of a user will be taken with full user permission.
- The picture will be passed through a Microsoft Cognitive Services API which can predict an accurate emotional state of the user.
- Based on the predictions, a song will be chosen from the backend database.
- The song will then be presented to the user to be played on Spotify.

# Technology used

- App logic - Kotlin
- Backend - Firebase
- Scripting - Python
- UI Layouts and elements - XML

## Libraries used:

- Retrofit
- GSON
- Kotlin Coroutines