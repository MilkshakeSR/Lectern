<p align="center"><img src="screenshots/3-lecture.png" alt="A Lectern lecture page: structured notes generated from the slides on the left, with the slides beside them on the right" width="900"></p>

# Lectern

**Your whole degree in one calm place.**
Organise every subject, turn lecture slides into great notes automatically, write your own, study with flashcards
and quizzes, plan your week and get advice for each subject. Everything is saved as normal files in a folder you choose.

<p align="center">
  <a href="https://github.com/MilkshakeSR/Lectern/releases/latest/download/Lectern.dmg">
    <img src="https://img.shields.io/badge/Download-Lectern%20for%20Mac-7A5AF0?style=for-the-badge&logo=apple&logoColor=white" alt="Download Lectern for Mac" height="56">
  </a>
</p>

## Screenshots
| Home dashboard | A subject and its Study Coach | Flashcard review |
| --- | --- | --- |
| ![Home dashboard](screenshots/1-dashboard.png) | ![Subject home](screenshots/2-subject.png) | ![Flashcard review](screenshots/4-flashcards.png) |

## Features
- **Slides → notes.** Paste a link to a PDF, PowerPoint, Word file, web page or Google Slides, sign in to iLearn once in Lectern's built-in browser, or just drop the file in. Claude writes structured notes: an overview, learning objectives, topic notes with clickable **slide citations**, diagrams explained, key terms, a summary, likely exam questions and things to ask your lecturer. You see the estimated cost first.
- **Slides beside your notes.** Click a slide to see which notes came from it, or click a citation to jump to the slide.
- **A friendly editor.** Type “/” for headings, checklists, callouts, toggles, tables, code and maths (KaTeX); “[[” to link pages; select text to **Explain**, **Simplify** or **Make a flashcard**. Pages are Markdown, so they open in any editor.
- **Flashcards that stick.** Basic, reversible, cloze and image-occlusion cards scheduled with **FSRS**, the modern spaced-repetition algorithm. Daily reviews, cram and weak-card modes, stats, CSV and Anki export.
- **Quizzes and practice exams** from any page, folder or subject, with written answers marked against your notes.
- **Study Coach** for every subject: what to focus on this week, weak topics, how to prepare for the next assessment, techniques that work, and “Plan my week”. **Ask about this subject** answers from your own notes and slides, with sources.
- **Planner, timer and grades:** a week/month planner (optional Apple Calendar sync), a Pomodoro timer in the menu bar that logs study time, and a grade calculator with HD/D/Cr/P/F bands.
- **Find anything:** instant search across pages, slide text, recording transcripts and flashcards, plus a command palette (⌘K).
- **Yours, as files:** subjects are folders and pages are Markdown, in a University folder you choose. Put it in iCloud Drive or OneDrive for automatic backup. Version history keeps 50 versions of every page, and deleted items go to the Trash.
- Lecture recordings can be **transcribed on your Mac** and used with the slides (for personal study only, per your university's rules).
- Export to PDF, Markdown or HTML, print, or make a subject **study guide** PDF. Light and dark mode, keyboard shortcuts for everything, and VoiceOver labels throughout.

## Requirements
- A Mac with Apple Silicon (M1 or later)
- macOS 14 Sonoma or later
- AI features need your own Claude API key from [platform.claude.com](https://platform.claude.com) (a lecture's notes usually cost a few cents). Everything else works without one, and offline.

## Install
1. [Download Lectern.dmg](https://github.com/MilkshakeSR/Lectern/releases/latest/download/Lectern.dmg) and open it.
2. Drag **Lectern** into **Applications**.
3. The first time, **right-click Lectern and choose Open**, then click **Open** again. Lectern isn't notarized by Apple, so macOS asks once.
4. The welcome screens help you choose your University folder, add a subject and (optionally) your Claude API key.

## Updates
Lectern checks for updates once a day and tells you when a new version is ready. You can also choose
**Lectern → Check for Updates…**, or turn on automatic installs in **Settings → Updates**.

## Privacy
Your notes, flashcards and quizzes stay in your University folder; the search index and page history stay on your Mac.
**Only the content used for an AI action is sent to Anthropic, and only when you click it** (for example, a lecture's slides when you click Generate Notes), using your own API key, which is kept in your Keychain.
Recordings are transcribed on-device. There are no analytics or tracking. Lectern also contacts the sites of links you paste, and GitHub to check for updates.

**Academic integrity:** Lectern is for learning. It explains, quizzes and gives feedback, but won't write your assessments.

## Report a problem
Choose **Help → Report a Problem…** in Lectern, or [open an issue](https://github.com/MilkshakeSR/Lectern/issues/new).

## Version history
See [all releases](https://github.com/MilkshakeSR/Lectern/releases).
