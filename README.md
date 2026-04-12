# Adventlify

> A church presentation desktop app built for Seventh-day Adventist congregations.

Adventlify is an Electron-based application that allows church media teams to project scripture, hymns, songs, programs, and countdowns to a secondary display — all from a single, easy-to-use interface.

---

## Features

### Bible
- Search and browse the Bible by book, chapter, and verse
- Project selected verses to the external display with large, readable typography
- Adjustable font sizes (up to 8xl)
- AI-powered Bible search *(licensed users)*
- Verse history tracking

### Hymnal
- Browse the hymnal by title, category, or alphabet
- Project hymn verses to the external display
- Remembers the last selected hymn across sessions
- AI-powered hymnal search *(licensed users)*
- Customizable font size

### Program Builder
- Create and manage worship programs/agendas
- Drag-and-drop item ordering
- Project program parts and participant names to the external display
- Export and print programs as PDF
- Date picker for organizing programs by date

### Special Songs
- Create and store custom song lyrics
- Edit song titles and content
- Project songs to the external display
- Font size adjustment
- Delete and manage song library

### Bible Study / Lesson
- Quarter-based lesson organization with week navigation
- Browse and display Bible study content
- Select and highlight verses within lessons
- Context menu for lesson verse actions

### AY Games
- 12 built-in Adventist Youth game modes:
  - Jumbled Letters, Guess The Word, Forbidden Words, Word Roulette
  - Bible Trivia, Bible Charades, Bible Pictionary, Bible Jeopardy
  - Scavenger Hunt, Bible Hangman, Bible Taboo, Mad Gab

### Countdown Timer
- Set hours, minutes, and seconds
- Custom title, message, and finished message
- Font size scaling (0–200%)
- Animated countdown projected to the external display
- Start, pause, and reset controls

### Calendar
- Full calendar view for scheduling church events
- Multi-month year view with weekend highlighting

### Settings
- Set custom backgrounds (image, video, or solid color) per screen type
- 12 preset color options with thumbnail previews
- Multi-display detection — choose which monitor to project to
- License status display

---

## Projection Screens

Adventlify manages a secondary window on the selected display for each content type:

| Screen | Content |
|---|---|
| Bible | Scripture verse with title |
| Hymnal | Hymn text with verse |
| Songs | Special song lyrics |
| Program | Program part and participant name |
| Generic | Custom freeform text |
| Countdown | Animated countdown timer |
| Default | Welcome / splash screen |

All screens support custom image, video, or color backgrounds configured in Settings.

---

## Tech Stack

- **Electron** 25 + **React** 18 + **TypeScript**
- **SQLite** (Bible, hymnal, and user data)
- **Tailwind CSS** + **Ant Design**
- **Zustand** (state management)
- **React DnD** (drag and drop)
- **@react-pdf/renderer** (PDF export)
- **FullCalendar** (calendar view)

---

## Development

Install dependencies:

```bash
npm install
```

Start in development mode:

```bash
npm start
```

Package for production:

```bash
npm run package
```

---

## License

MIT
