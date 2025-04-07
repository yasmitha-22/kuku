# 🎧 My Daily Soundtrack – Kuku FM

Welcome to **My Daily Soundtrack**, a GenAI-powered feature designed for [Kuku FM](https://kukufm.com), to enhance user engagement by delivering personalized audio suggestions based on daily moods. With just a tap, users can start their day with content that resonates with how they feel.

---

## 🔗 Live Demo

👉 [Try It Out Here](https://yasmitha-22.github.io/kuku/)  


---

## 🎯 Vision & Objective

The primary goal of this feature is to:

- 🎧 Increase **daily time spent** in the app.
- 📲 Boost **app open rates** through daily engagement triggers.
- 🌟 Provide a **personalized listening journey** that adapts to users’ moods.
- 🔁 Build **habitual use** with streaks, reminders, and rewards.

---

## 🧠 Introduction

In today’s fast-paced world, users crave content that aligns with how they feel. *My Daily Soundtrack* solves this by offering a seamless GenAI interface that suggests curated playlists, stories, quotes, and affirmations based on the user’s emotional state. Whether you're feeling joyful, tired, or somewhere in between, your perfect audio moment awaits.

---

## 🔬 Explanation

The project begins with a mood selection screen featuring five emotions: 😊 Happy, 😐 Neutral, 😢 Sad, 😡 Angry, 😴 Tired.

When a user selects a mood:
- A `JavaScript` function captures the mood and enables the “Start My Soundtrack” button.
- On click, the screen transitions and dynamically populates the UI with:
  - 📚 A related book summary
  - 💬 A quote
  - 📖 A short story
  - 🌟 A positive affirmation
  - 🎧 A suitable audio clip

The suggestion list is stored in a `moodSuggestions` object that maps each mood to an array of personalized recommendations.

Bonus features like **daily reminders** and **streak rewards** are shown to encourage recurring engagement.

---

## 🛠️ Implementation Plan

1. **Mood Selector UI** – Friendly, emoji-driven design to capture the user's current emotional state.
2. **Suggestion Generator** – JavaScript logic maps moods to curated content like book summaries, quotes, audio clips, etc.
3. **Dynamic Transition** – Smooth switch to suggestion screen with tailored recommendations.
4. **Feature Highlights** – Display bonus features like listening reminders and reward streaks.
5. **Live Deployment** – Host on GitHub Pages for public access and demonstration.

---

## ✨ Key Features

- 🎭 Mood-based content curation
- 🔁 Listening streak tracker (3/5/10 days)
- ⏰ Daily listening reminder (optional)
- 🌄 Clean UI with motivational, wellness-based content
- ⚡ One-click refresh to regenerate suggestions

---

## 🧰 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Design:** Responsive, emoji-based UX with `Poppins` font
- **Hosting:** GitHub Pages
- **Extensions (Future):** LocalStorage, Push Notifications, API Integration

---

## 🔮 Future Scope

- 🌐 Backend Integration for real-time content updates
- 🧠 AI/LLM integration to auto-generate recommendations
- 📱 Mobile app expansion using React Native or Flutter
- 🔔 Push notifications for daily reminders
- 📊 Mood analytics for better user insights

---

## 📈 Success Metrics

- 📥 High mood-selection conversion rate
- 📆 Repeat visits (measured via streak tracking)
- 🧘‍♀️ User satisfaction with personalized content
- ⏱️ Time spent per session
- 🔔 Reminder opt-in percentage

---

## ⚔️ Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Creating a personalized experience with static data | Structured mood-based suggestion sets |
| Keeping the UI minimal yet engaging | Used gradient backgrounds, emojis, hover effects |
| Ensuring cross-device usability | Responsive CSS and minimal JS dependencies |
| Encouraging habit formation | Implemented rewards for streaks and reminders |

---

## 📬 Contact

Feel free to reach out for feedback or collaboration:

**Yasmitha Tanikonda**  
📧 [yasmithatanikonda@gmail.com]  

---

## 🙏 Thanks

Thanks to the Kuku FM team for the opportunity to imagine creative ways to drive deeper user connection through sound.

---

## ⚠️ Disclaimer

This project is a conceptual prototype built for demonstration purposes. It does not represent an official Kuku FM product or feature at this stage.

---

