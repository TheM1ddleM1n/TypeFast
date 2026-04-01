# ⌨️ Typefast
**Think fast. Type faster.**

A high-octane, minimalist typing challenge where speed and accuracy are your only lifelines. Modeled after Roblox's Spelling Bee — with a live announcer, per-word WPM tracking, and boss words that will break you.

[**PLAY NOW!**](https://them1ddlem1n.github.io/TypeFast/)

---

## 🕹️ How to Play
- **Listen up:** The announcer reads every word aloud — *"Spell the word…"* / *"Alright, spell the word…"*
- **Type the Word:** Enter the word shown on screen.
- **Auto-Submit:** No Enter key needed — the game validates the instant you finish.
- **Manual Submit:** Press Enter to submit early (wrong answer = instant elimination).
- **Survive the Scale:** Words get longer and harder, and the timer shrinks as your streak grows.
- **Game Over:** Time runs out or you spell a word wrong — you're eliminated.

---

## ⚡ Key Features

### 🔊 Announcer Voice
- Every word is read aloud using the Web Speech API — no libraries, no downloads needed.
- First word: *"Spell the word. [word]"* — subsequent words: *"Alright, spell the word. [word]"*
- Automatically selects the best available voice on your device.
- Toggle on/off from the main menu with a live speaking indicator.

### 📊 Roblox-Style WPM
- WPM is calculated **per word**: `(chars / 5) / minutes` — measuring exactly how fast you typed *that* word.
- Flashes big in gold above the word after every correct submission.
- Live WPM updates as you type the current word.
- End screen shows your **Best WPM** and **Average WPM** across the whole run.

### 🔥 Adaptive Difficulty
- **5 difficulty tiers:** Easy → Medium → Hard → Expert → Boss
- **Streak pressure:** Every 3 consecutive correct words shrinks the timer by 1 second (up to −4s).
- **Combo multipliers:** 5+ streak = 2× points · 10+ streak = 3× points with fire indicators.
- **Boss Words 💀:** Every 10th word is a legendary spelling nightmare with a tighter timer.

### 💀 Boss Word Hall of Shame
Includes some of the most unhinged words in the English language:
- `chargoggagoggmanchauggagoggchaubunagungamaugg`
- `pneumonoultramicroscopicsilicovolcanoconiosis`
- `antidisestablishmentarianism`
- `floccinaucinihilipilification`
- `hippopotomonstrosesquippedaliophobia`
- etc

### 🎯 Stats & Tracking
- Per-run stats: Best WPM, Average WPM, Accuracy, Best Streak
- Persistent high score across sessions (localStorage)
- Eliminated overlay shows what you typed vs. the correct spelling

---

## 🛠️ Built With
- **JavaScript (ES6):** Game logic, Web Speech API, DOM manipulation
- **CSS3:** Animations, responsive layout, theme variables
- **HTML5:** Zero dependencies — single file, runs anywhere

---

## 📈 Want to Improve Your Score?
Practice finger placement on [TypingClub](https://www.typingclub.com) or benchmark your raw speed on [Monkeytype](https://monkeytype.com).

---

#### Developed by TheM1ddleM1n
