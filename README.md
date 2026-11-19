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
| Summary Studio | A mind map summary | One-page cheat sheet |
| --- | --- | --- |
| ![Summary Studio: format, length and focus options beside a live preview with a verification report](screenshots/8-summary-studio.png) | ![A mind map summary drawn from a lecture, with zoom and export](screenshots/9-mind-map.png) | ![A dense one-page cheat sheet summary](screenshots/10-cheat-sheet.png) |

| Active recall | Past paper practice |
| --- | --- |
| ![Active recall: key terms blurred until you reveal them](screenshots/11-active-recall.png) | ![Practising a past exam question with marking against the lectures](screenshots/12-past-paper.png) |

| The new editor and a page's flashcards | Planner week view | Export a subject as one PDF |
| --- | --- | --- |
| ![Floating formatting menu and the page flashcard panel](screenshots/5-editor-and-cards.png) | ![Planner week view](screenshots/6-planner.png) | ![Export sheet](screenshots/7-export.png) |

| Home dashboard | A subject, with its Flashcards section | Flashcard review |
| --- | --- | --- |
| ![Home dashboard](screenshots/1-dashboard.png) | ![Subject home](screenshots/2-subject.png) | ![Flashcard review](screenshots/4-flashcards.png) |

## Features
- **Summary Studio.** Summarise any lecture, reading or recording in 17 formats (bullets, Cornell notes, tables, Q&A, glossary, mind map, timeline, flowchart, one-page cheat sheet, TL;DR, slide by slide, formula sheet and more), at any length and level, focused on what you choose, in your language. Save presets, and set a default for each subject.
- **Summaries you can check.** Lectern pulls out the facts first, writes from them, then checks every statement against the slides it cites. Anything it can't confirm is marked "⚠ check" with the source on hover, and a report shows slides covered and statements verified. In our benchmark with a small local model, recall rose from 80% to 98% and faithfulness from 90% to 99% versus 1.5 (see the release notes).
- **Reads your files properly.** Headings, tables, two-column PDFs, speaker notes, formulas, scanned pages (on-device OCR), captions (.srt/.vtt), EPUB books and web articles. Headers, footers, "Questions?" slides and duplicates are cleaned out first.
- **Summarise everything at once.** A Processing Queue works through a whole subject in the background, and can wait until your Mac is plugged in and idle.
- **Practise, don't just reread.** Active recall with blurred key terms, timed blurting, Feynman mode (explain it to a curious AI student), and a Daily Review on Home.
- **Past papers.** Import past exams, practise or sit a timed mock with marking against your lectures, see likely exam topics, and get a readiness score with a one-click revision plan.
- **Listen.** Pages read aloud with a natural voice, or exported as an audio file with chapters for the bus.
- **Search by meaning** with a local embedding model, **smart folders**, and a **graph** of how your pages link.
- **Quick capture** from any app with ⌃⌥Space (notes, links, screenshots with their text read for you), or Services → Send to Lectern.
- **References** in APA 7, Harvard, MLA, Chicago or IEEE from a DOI or ISBN, with in-text citations and BibTeX.
- **Reading mode** with comfortable spacing, a reading ruler and a dyslexia-friendly font, a templates gallery, and daily backups you can restore from.
- **Slides → notes, any length.** Paste a link to a PDF, PowerPoint, Word file, web page or Google Slides, sign in to iLearn once in Lectern's built-in browser, or just drop the file in. Lectern reads every slide in sections and writes structured notes: an overview, learning objectives, topic notes with clickable **slide citations**, diagrams explained, key terms, a summary, likely exam questions and things to ask your lecturer. A coverage report shows every slide was covered, and lists any that weren't. It runs in the background and can resume if it's interrupted.
- **Claude or free local models.** Use your own Claude key, or Ollama on your Mac. The Model advisor recommends the best installed model for your Mac, and you can choose a different model for each task.
- **Slides beside your notes.** Click a slide to see which notes came from it, or click a citation to jump to the slide.
- **An editor like Notion and Google Docs.** Select text for a formatting menu (type, size, colour, highlight, alignment, links, AI). An optional toolbar, drag handles on every block, and a “/” menu with tables, toggles, callouts, columns, code, maths (KaTeX), dates and a table of contents. Pages stay Markdown, so they open in any editor.
- **Your files and your order.** A paperclip on every page lists everything added to it, and you can drag pages, lectures and quizzes into any order. New ones go to the bottom of the folder.
- **Flashcards that stick.** Rich-text basic, reversible, cloze and image-occlusion cards scheduled with **FSRS**, the modern spaced-repetition algorithm. Every page has its own cards beside your notes, and each subject shows them all by folder, with strength, due counts and “Study selected”. Daily reviews, cram and weak-card modes, stats, CSV and Anki export.
- **Quizzes and practice exams** from any page, folder or subject, with written answers marked against your notes.
- **Study Coach** for every subject: what to focus on this week, weak topics, how to prepare for the next assessment, techniques that work, and “Plan my week”. **Ask about this subject** answers from your own notes and slides, with sources.
- **A planner built for semesters.** Week numbers (Macquarie's dates built in), your class timetable with .ics import, tasks with natural-language quick add, assessment milestones, **Plan My Week**, an “I'm behind” catch-up, exam revision plans, Day, Week, Month, Semester and Agenda views, reminders, and optional Apple Calendar and Reminders sync.
- **Timer and grades:** a Pomodoro timer in the menu bar that logs study time, and a grade calculator with HD/D/Cr/P/F bands.
- **Find anything:** instant search across pages, slide text, recording transcripts and flashcards, plus a command palette (⇧⌘P).
- **Yours, as files:** subjects are folders and pages are Markdown, in a University folder you choose. Put it in iCloud Drive or OneDrive for automatic backup. Version history keeps 50 versions of every page, and deleted items go to the Trash.
- Lecture recordings can be **transcribed on your Mac** and used with the slides (for personal study only, per your university's rules).
- **Export a whole subject or folder as one PDF** with a cover, contents, bookmarks and page numbers; or export Markdown or HTML, print, or make a **study guide** PDF. Light and dark mode, keyboard shortcuts for everything, and VoiceOver labels throughout.

## Requirements
- A Mac with Apple Silicon (M1 or later)
- macOS 14 Sonoma or later
- AI features need either your own Claude API key from [platform.claude.com](https://platform.claude.com) (a lecture's notes usually cost a few cents) or [Ollama](https://ollama.com) (free, runs on your Mac). Everything else works without AI, and offline.

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
**With Claude, only the content used for an AI action is sent to Anthropic, and only when you click it** (for example, a lecture's slides when you click Generate Notes), using your own API key, which is kept in your Keychain. With Ollama on your Mac, nothing leaves your Mac.
Recordings are transcribed on-device, and OCR, read-aloud and semantic search all run on your Mac. There are no analytics or tracking. Lectern also contacts the sites of links you paste, Crossref and Open Library when you look up a DOI or ISBN (only that number is sent), and GitHub to check for updates.

**Academic integrity:** Lectern is for learning. It explains, quizzes and gives feedback, but won't write your assessments.

## Report a problem
Choose **Help → Report a Problem…** in Lectern, or [open an issue](https://github.com/MilkshakeSR/Lectern/issues/new).

## Version history
See [all releases](https://github.com/MilkshakeSR/Lectern/releases).
