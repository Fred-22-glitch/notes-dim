# Changelog

## 0.3.2
- Study AI (Pro), in the note's ⋯ menu: summary and main topics appended to the note, quote wall, flashcards, exam study plan, automatic mind map and ABNT reading notes. Everything runs on-device. Each task splits the note into chunks, constrains the model output to a JSON schema and drops results that aren't grounded in the note (quotes are picked by sentence number, so they are always verbatim).
- External AI prompts (summary, quotes, study plan) for long texts; the pasted reply is brought back into the app.
- Windows: new default model Qwen3-4B-Instruct-2507 (2.5 GB, Apache 2.0); Qwen3 1.7B stays as the faster option and is the Android model. Qwen 2.5 1.5B was removed (worst in testing) and its file is deleted automatically. Qwen2.5-3B was tested and left out because its license doesn't allow commercial use.
- Pro screen shows how the AI will perform on the device (RAM and CPU) before buying.
- Calendar: note reviews, flashcards due and dates/tasks written in notes; tapping a day creates a journal, meeting, class or to-do note with the date filled in.
- 8 themes: Graph paper, Coffee, Marble and gold, Heirloom notebook, Watercolor, Polaroid (free); Vintage cassette and Soft cyberpunk (Pro). WCAG AA contrast is checked by a test; textures only in the margins.
- Flashcards are now free, with hand-written cards. AI in flashcards stays in Pro.
- Free templates: ABNT reading notes (form that builds the cover, reference and page-numbered quotes), exam schedule and mistakes notebook.
- Android AI: Cancel now terminates the wllama worker immediately (wllama only checks the abort signal between tokens); a cancelled run no longer unloads the model under the next one; 700-char chunks, shorter outputs and a 6-minute limit per chunk (partial results are kept). The progress shows the model-loading stage and elapsed time; the time estimate is learned per device.
- Reading mode (Pro): read-aloud bar shows the sentence and highlights the current word (speechSynthesis boundaries on Windows, TextToSpeech onRangeStart on Android).
- New menu puts text notes first with an "Other types" group; Export puts PDF and share image first; templates show a one-line description; trash has a prominent "Empty trash" and scrolls vertically only.
- Fixes: trashed note came back (Windows with vault); Vault panel didn't open; review mode has its own bar and "Exit review"; footer bulb toggles spaced review; mind map treats "Topic:" lines and bold paragraphs as headings; imported .md no longer glues lines together; AI on Android works again (wllama compat build bundled); double top inset on Android.

## 0.3.1
- Flashcards (Pro): New → Flashcards from a note. Questions are generated offline from the note (hidden text, bold, definitions, lists, tables, dates, labeled arrows). Flip the card and mark Got it / Almost / Missed it; reviews use spaced repetition, with mastery and progress charts. The deck updates when the source note changes.
- Flashcards: on-device study AI (optional 1.1 GB download, Qwen3 1.7B or Qwen 2.5 1.5B GGUF). Windows runs it natively through node-llama-cpp (Vulkan when available); Android and the web build use wllama (llama.cpp compiled to WebAssembly). Output is constrained to a JSON schema and filtered: answers must be grounded in the note, near-duplicate and author questions are dropped. Notes never leave the device.
- Flashcards: copyable prompt for ChatGPT/Gemini/Claude; paste the reply back to add cards (text notes only).
- Cleaner top bar: Listen, Mind map, Share, folder and favorite moved to the ⋯ menu; dark mode moved to ⚙ Settings.
- Arrows can be bent by dragging their middle (double-click the middle to straighten).
- Arrows always point from the block you dragged from to the block you dropped on, and have a larger hit area.
- Arrows: dropping an arrow near the right side of a shape now connects to that side instead of jumping to the left.
- Windows: the window opens maximized without the white title bar; F11 toggles full screen.
- Canvas corner controls (zoom, fit, undo) restyled to match the app.
- Creating a note: right-click the background on Windows, long-press on Android. Double-click/double-tap no longer creates notes.
- Dropping an arrow on empty space no longer creates a note; arrows only connect when dropped on another block.
- Android: arrows are easier to hit with a double-tap to delete them.
- Android: dragging the canvas across sticky notes and frames no longer gets stuck.
- Read aloud: reads the selected text or sticky note instead of starting from the top.
- "Appearance and sizes" is now "Settings", with a default note font option; "Support" sits right below "How it works".
- Notebook PDF: every line of text, list item and checkbox sits on the ruled line.
- Pro features show a preview before asking for activation.
- Vault: the button always opens the panel, with instructions for syncing through the cloud.
- The sidebar closes by itself when opening templates, the notebook PDF and the share image.

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
