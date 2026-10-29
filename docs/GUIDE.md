# Guide

The same guide as in the app (⚙ → How it works). Labels below are from the English version of the app.

## Creating notes and blocks

- Right-click the canvas background to add a note, rectangle, ellipse, frame or table (a 3 × 3 table that is ready to type in). Shortcuts: N, R, E, Q and T.
- Text notes and canvas notes are created from "New" at the top of the notes list.

**Android:** long-press the background for the menu.

## Moving and resizing

- Drag a note by the ⠿ strip at its top. Dragging the text doesn't move the note.
- With a note selected, drag its sides, bottom or corners to resize (the grab area extends a little outside the note).
- Moving, resizing and creating snap to the dot grid; hold Alt to move freely.
- A note can't be dragged out of view; "Show all" brings every note back into view.
- The toolbar above the note changes color, links to another note, duplicates and deletes.

**Android:** same strip at the top; the resize edges are wider. When you start typing, the canvas scrolls so the note stays above the keyboard.

## Selecting several notes

- Hold Shift and drag on the background to select with a rectangle, or Ctrl-click notes.
- With two or more notes selected, a bar appears to align, distribute and group them in a frame.

**Android:** tap the Lasso button (next to the magnifier) and drag your finger around the notes. Then drag one of them to move them all.

## Connecting blocks with arrows

- Hover or select a note to show the blue dots on its four sides. Drag a dot onto another block.
- Drop the arrow on another block to connect them. Dropping it on empty space does nothing.
- Right-click an arrow to change its head, color, dash style or add a label. Double-click an arrow to delete it.
- Drag the middle of an arrow to bend it. Double-click the middle to straighten it.

**Android:** select the note to show the dots. Long-press an arrow to edit it; double-tap to delete it.

## Links between notes

- Create one with the link button in the formatting bar, Ctrl+K, or by typing `[[` and picking a note (or creating one).
- Double-click a link to open the linked note. A single click only places the cursor.

**Android:** same, without Ctrl+K. Double-tap to open.

## Read-only mode

- Click "Edit" at the top to switch to "Read" (lock icon). The top bar and the formatting bar hide; you can read, scroll and follow links, but nothing changes.
- "Stop reading" in the corner goes back to editing. The mode is saved per note.

**Android:** in the ⋯ menu.

## Text notes: formatting

- The font, size, heading and line spacing lists preview on the selected text while you hover them (or slide a finger over them). Click (or lift your finger) to apply it as a single undo step; leaving the list puts the text back.
- The size box takes any whole number from 8 to 96; − and + change it by one.
- Right-click a misspelled word for suggestions, "Ignore" (until you close the app) and "Add to dictionary" (Windows). The dictionary follows the app language.
- Creating a table while the cursor is in a table puts the new one right after it.
- Renaming the top heading of a text note renames the note, and renaming the note at the top renames the heading.

## Mistakes notebook

- New → Other types → Mistakes notebook. Each mistake has subject, topic, source, type of mistake, confidence, tags and date, and one or more questions (and sub-questions) with the question, your answer, the right answer and an explanation. These fields are long text with formatting; the formatting bar at the top works in them, images included.
- Search, and filter by subject, type of mistake and status ("to review today", "review", "mastered").
- "Reviewed: Remembered / Got it wrong again" schedules the next review at 1, 3, 7 and 14 days; after the last one the mistake is marked as mastered.

## General review

- Target button next to the calendar. Pick folders, mistake-notebook subjects, tags and a date range (nothing picked means everything) and build the session.
- Mistakes come first (those due for review first): the answer shows only when you ask, and Remembered / Missed schedules the next review. Then the notes: open each one or skip to the next.

## Mark text for flashcards

- Select text and click the eye icon in the formatting bar: the marked text becomes a blank in the flashcards made from the note.

## Flashcards

- New → Other types → Flashcards from a note, then pick a note. Questions are generated offline from it: hidden text, bold/highlighted words, "term is explanation" and "term: explanation" sentences, headings with lists, tables, dates and labeled canvas arrows. The deck is listed with your notes and is refreshed when the source note changes.
- Pick how many cards to study and whether they are shuffled. Tap the card to flip it, then mark Got it / Almost / Missed it (on touch devices, swipe right, left or up). Missed and almost cards come back later in the same session. Spaced repetition schedules the rest at 1, 3, 7, 15, 30 and 60 days.
- "Write a card" adds a question by hand. Use the trash icon on a card to drop it from the deck.
- Pro: the study AI reads the note and writes the questions on your device, and "Use an external AI" gives you a prompt with the note text and the expected `Q:`/`A:` format to paste into any chatbot (text notes only).

## Study AI (Pro)

- In a note, open the ⋯ menu and tap "Study AI": smart summary and main topics (appended to the note), quote wall (a "Quote wall" note), flashcards, study plan between a start date and an exam date (a task list that shows up on the calendar) and automatic mind map. Flashcard generation keeps running if you switch notes.
- The model is downloaded once and runs offline: Qwen3 4B (2.5 GB) or Qwen3 1.7B (1.1 GB) on Windows; Qwen3 4B on Android phones with 6 GB of RAM or more (with less, use the external-AI prompt). It is loaded when a task starts and unloaded when it ends.
- Each chunk of the note takes seconds on a PC with a GPU and about a minute on a phone. On a phone each chunk has a 6-minute limit; if it is exceeded, the task stops and keeps what was already done. Cancel stops it right away.
- For long texts, "Very long text? Use an external AI" gives you a prompt for the summary, quotes or study plan; paste the reply back and the app brings it in.

## Notes list and search

- ‹ › next to ☰ go back and forward through opened notes (Alt+←/→).
- Ctrl+click (or long press) notes in the list to move or trash several at once.
- Magnifier in the page corner (or Ctrl+F) finds words in a text note.

## Calendar

- Calendar button next to the search box: reminders, and dates written in notes (27/10/2026, 2026-10-27; in English, 10/27/2026), including tasks such as the study plan. Each day shows an icon and a count per type.
- Tap a day to see what is on it, add a reminder, or create a journal, meeting, class or to-do note with the date filled in.
- Reminders have no time: they show up once when you open the app on that day.

## Themes and size

- ⚙ → Theme: Notebook (follows dark mode), Graph paper, Coffee, Marble and gold, Heirloom notebook, Watercolor, Polaroid. Vintage cassette, Soft cyberpunk and Melted ice cream are Pro and animated (turn it off under Settings → Appearance). Each theme restyles the whole app.
- ⚙ → Size: interface and note text.

## Read aloud

- Open the ⋯ menu at the top and click "Listen" and the app reads the whole note. Select some text first to hear only that part.
- The reading speed is in ⚙. With Pro, the reading bar shows the sentence and highlights the current word.

**Android:** in the ⋯ menu.

## Text notes: scroll or book

- At the top, choose "Scroll" (continuous page) or "Book" (side-turning pages).
- In book mode, the page button with a + in the bottom bar adds a blank page.

**Android:** in the ⋯ menu.

## Text → mind map (Pro)

- In a text note, open the ⋯ menu at the top and click "Mind map": headings become blocks connected to the main topic, and the text under each heading goes inside its block. A new canvas note is created; the original stays as it is.

## Drawing

- On the canvas: pencil button at the top. Pen, highlighter and eraser, each with three sizes; the eraser only erases where it passes.
- Inside text: pencil button in the formatting bar. The drawing becomes an image; select it and use "Edit drawing" to edit it again.

## Notebook PDF and share image

- Export → "Notebook-style PDF" prints the note as a lined notebook page.
- "Share as image" in the ⋯ menu creates a story-sized (1080×1920) or square image of the note. On Android it opens the system share sheet; on Windows you can save or copy it.

## Undo

- Canvas: undo/redo in the corner controls (Ctrl+Z / Ctrl+Y). Inside text, use undo in the formatting bar.
- Versions: "Versions" in the info bar keeps a copy of the note every 10 minutes of editing.

## Vault, backups and syncing

- The vault ("Vault" button below the notes list) is the folder where notes are stored. Pick a Syncthing folder to have the same notes on PC and phone.
- Backups run automatically. Use Export to save a full backup at any time.

## Notes Dim Pro

- ⚙ → Notes Dim Pro shows what Pro includes, how the study AI is expected to run on your device (RAM and CPU), how to buy it (Ko-fi) and where to paste the activation key.
- With a synced vault, the key activates Pro on your other devices automatically.

## Updates

- When a new version is out, a notice with "Update" appears. You can also check under ⚙ → Check for updates.

---

[Back to README](../README.md)
