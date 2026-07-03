# Minimalist Notes App

Ek lightweight, responsive, aur modern note-taking application jo Kotlin aur Android SDK ka use karke banayi gayi hai. Is app ko khas taur par mobile aur tablet dono par seamlessly kaam karne ke liye design kiya gaya hai.

## Key Features
- **Responsive Design:** Tablet par sidebar view aur phone par compact view (Programmatic UI).
- **Rich Text Formatting:** Bold, Italic, aur Underline support using Spannable strings.
- **Backup & Restore:** Locally notes ko export (txt) aur import karne ki suvidha (Available in Settings).
- **Modern Dark UI:** Minimalist, sleek, aur dark-theme design.
- **Undo/Redo:** Typing mistakes ko sudharne ke liye history support.
- **Real-time Word Counter:** Note likhte waqt live count.

## Tech Stack
- **Language:** Kotlin
- **UI:** Programmatic UI (No XML files used - designed for AIDE stability)
- **Environment:** Designed for AIDE (Android IDE)

## Setup Instructions (AIDE Users)
1. AIDE mein naya project create karein ya purana project open karein.
2. `MainActivity.kt` aur `NoteEditActivity.kt` ko open karein.
3. Code ko di gayi files se completely replace karein.
4. **Important:** Compile karne se pehle `Clean Project` par click karein taaki purani cache/resources saaf ho jayein.
5. App ko `Run` karein.

## Why Programmatic UI?
Humne XML files (layout) ka use nahi kiya hai taaki AIDE mein resource compilation issues (R.layout errors) se bacha ja sake. UI ka har element Kotlin code se generate ho raha hai, jisse build process zyada stable rehti hai.

## Project Structure
- `MainActivity.kt`: Master controller, tablet sidebar logic, backup/restore logic, aur list management.
- `NoteEditActivity.kt`: Focused editor activity for phone, formatting support, aur undo/redo logic.

---
Built with ❤️ for AIDE developers.
