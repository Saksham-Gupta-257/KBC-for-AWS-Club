# 📺 Kaun Banega Crorepati (KBC) - AWS Club Edition

An interactive, web-based trivia game inspired by the popular television show *Kaun Banega Crorepati* (Who Wants to Be a Millionaire). This application was specifically designed and developed for hosting an engaging quiz event for the **AWS Club**.

It features a fully functional frontend interface complete with authentic sound effects, video-based timers, and classic lifelines to recreate the immersive experience of the actual game show.

## ✨ Key Features

* **Authentic Lifelines:** Includes classic game lifelines with visual assets:
  * 🧍‍♂️ Audience Poll
  * 🌓 50:50
  * ✌️ Double Dip
  * 🔄 Switch the Question
  * 💡 Expert Advice
* **Immersive Audio Experience:** Fully integrated sound effects for locking answers, ticking timers, correct/incorrect responses, audience poll results, and the iconic background theme music.
* **Dynamic Video Timers:** Uses embedded video assets to handle countdown timers for different difficulty stages (30s, 45s, 60s, and 90s).
* **Custom UI/UX:** Styled to match the KBC aesthetic with custom backgrounds, logos, and money transfer graphics.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3
* **Logic & Interactivity:** Vanilla JavaScript
* **Media Handling:** Native HTML5 Audio and Video APIs

## 📂 Project Structure

The repository is organized to handle a large amount of media assets efficiently:

* `/css` - Contains the stylesheet (`index.css`) for the UI layout and game styling.
* `/js` - Contains the core game logic (`index.js`), handling question progression, timers, lifelines, and audio triggers.
* `/images` - UI assets, lifeline icons, and KBC-themed backgrounds.
* `/sounds` - A rich library of `.mp3` files for authentic game show sound effects.
* `/video` - `.mp4` files used for the dynamic countdown clocks.

## 🚀 How to Run Locally

Since this is a client-side vanilla web application, no complex build tools or servers are required to run it locally.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Saksham-Gupta-257/KBC-for-AWS-Club.git](https://github.com/Saksham-Gupta-257/KBC-for-AWS-Club.git)
