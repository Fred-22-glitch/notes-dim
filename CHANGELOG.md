# Changelog

## 0.3.0
- Languages: the app is now also available in English and Spanish (⚙ → language).
- Lasso on Android: tap the lasso button next to the magnifier and drag your finger around sticky notes to select several at once.
- Study streak: days in a row, weekly goal and calendar (the flame next to "Notes").
- Read aloud: the app reads the note or the selected text; in Review mode, hidden text isn't read.
- Notebook-style PDF: the note comes out as a lined notebook page, ready to print.
- Share image: creates a story-sized or square image of the note.
- Notes Dim Pro (one-time payment): text → mind map, study pack (exam prep by subject area, essay map, exam schedule, mistakes log, full ABNT reading notes) and PDF/image without the watermark, with extra papers and colors. Everything that was free stays free.

## 0.2.6
- Added a "Support" screen (⚙ → Apoie o Notes Dim) with Pix (QR code on desktop, copy-and-paste code, payment link) and Ko-fi for people outside Brazil.

## 0.2.5
- Reverted the 0.2.4 resize handles: they made the canvas stick when dragging with a finger.
- Dark theme: highlighted text is readable again.
- Added a third-party licenses screen (⚙).
- Updated the license (free to use; code and brand remain proprietary).
- New icon for the guide screen.

## 0.2.4
- Larger resize handles and edges on sticky notes, shapes and frames (reverted in 0.2.5).
- Added an in-app guide (⚙, or the ⋯ menu on Android) covering links, review, read-only mode, arrows, drawing and more.
- The eraser only erases where it passes, with three sizes and a size preview.
- Android: ⋯ menu reorganized into a labeled list ("Esta nota" / "App"); lock icon next to the title in read-only mode.
- Windows: same icon as Android, including window and taskbar.

## 0.2.3
- Windows: the installer closes any running instance before installing, fixing the "Não é possível fechar o Notes Dim" error during updates. The real cause was the desktop build bundling Capacitor/Android files with paths longer than 260 characters.
- Faster updates: silent install and differential download.

## 0.2.2
- Windows: the app saves a backup, closes its windows and installs the update silently, reopening on the new version. (Didn't fully fix the update error; see 0.2.3.)

## 0.2.1
- Asks where to store notes on first launch when no vault is set.
- Update check runs on launch, every 30 minutes and when the app regains focus; release notes are shown after updating.
- New icon; no more white border on Android.
- Moved the note toolbar away from the arrow handle.
- Links between notes open on double-tap/double-click to avoid accidental navigation.

## 0.2.0
- Custom icon set across the app (no system emoji).
- Text notes: scroll and book modes, with a button to add a blank page.
- In-app updates: ⚙ → Procurar atualização (installed Windows version and Android).
- Android: the drawer closes on swipe left or tap outside; dragging a note no longer pulls an arrow by accident.
- Error recovery screen and in-app privacy policy.
- APK signed with the project's own key.

## 0.1.0
- First release: canvas, text notes, freehand drawing, vault, backups, export and Android version.
