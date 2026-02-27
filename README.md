# 🎉 Interactive Birthday Blast Web Greeting

A premium, multi-step progressive web greeting built to deliver a highly interactive and memorable birthday surprise. It features a sequence of suspense-building messages, an interactive party popper, a custom-built physics-based confetti engine, and a 3D tilt glassmorphism reveal card.

## ✨ Features

* **Zero Dependencies:** Built entirely with pure HTML5, CSS3, and Vanilla JavaScript. No heavy frameworks or external libraries required.
* **Interactive "Party Popper":** Gamified interaction requiring the user to tap to build pressure before the final reveal.
* **Dynamic Particle Engine:** Custom physics-based directional confetti explosions and ambient floating balloons utilizing the highly performant Web Animations API.
* **3D Glassmorphism UI:** A modern, frosted-glass final greeting card that reacts and tilts in 3D space based on mouse/touch movement.
* **Immersive Audio:** Integrated background music that automatically plays upon the first user interaction (bypassing strict browser autoplay policies).
* **Fully Responsive:** Perfectly scales across mobile devices, tablets, and desktop screens.

## 🚀 Getting Started

Since this project requires no build tools or package managers, running it is as simple as opening a file.

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

## 🛠️ Customization Guide

You can easily personalize this greeting for anyone. Open `index.html` in your favorite code editor and locate the following sections:

### 1. Change the Birthday Person's Name
Scroll down to the `<script>` tag (around line 263). Change the `userName` variable to the birthday person's name.

```javascript
// Change "Sapthesh" to the recipient's name
const userName = "Sapthesh"; 
```

### 2. Customize the Messages
Right below the name variable, you can edit the dynamic typewriter text to say whatever you like.

```javascript
const messages = {
    1: `Hey ${userName}, guess what?`,
    2: "Today is your special day!",
    3: "Let's get this party started!"
};
```
*Note: To change the final greeting on the card, scroll to the HTML body (around line 254) and edit the text inside `<p class="message">`.*

### 3. Change the Music
By default, the project uses a free royalty-free track. To add your own favorite song, replace the source link inside the `<audio>` tag (around line 214) with any direct `.mp3` link.

```html
<audio id="bg-audio" loop preload="auto">
    <source src="[https://assets.mixkit.co/music/preview/mixkit-happy-party-152.mp3](https://assets.mixkit.co/music/preview/mixkit-happy-party-152.mp3)" type="audio/mpeg">
</audio>
```

## 🍴 How to Make Your Own (Forking)

Want to use this template to surprise your own friends or family? You can easily create your own copy of this repository!

1. **Fork the Repo:** Click the **Fork** button at the top right of this repository's page to create a copy in your own GitHub account.
2. **Clone your Fork:** Clone the repository to your local machine using `git clone https://github.com/YOUR-USERNAME/YOUR-FORKED-REPO-NAME.git`.
3. **Customize:** Follow the Customization Guide above to change the names, messages, and music in the `index.html` file.
4. **Commit & Push:** Save your changes, commit them, and push them back to your forked repository on GitHub.
5. **Deploy:** Follow the deployment steps below to get a live link!

## 🌐 Getting Your Shareable Link (Deployment)

Want to send this to a friend right now? Because this is a single HTML file, you can host it 100% for free and get a live web link in under 2 minutes. No servers or complex hosting required!

**Option A: GitHub Pages (Easiest for Forked Repos)**
If you just forked this repository and made your changes, GitHub will host it for you automatically!
1. Go to your repository's **Settings** tab.
2. Click on **Pages** in the left sidebar.
3. Under "Build and deployment", change the source branch from `None` to `main` (or `master`) and click **Save**. 
4. Wait about 1–2 minutes, refresh the page, and GitHub will display your free, live URL at the top! Send that link to the birthday VIP.

**Option B: Vercel (Drag & Drop)**
If you downloaded the files to your computer instead of forking:
1. Go to [Vercel](https://vercel.com/) and create a free account.
2. Drag and drop your project folder directly into your dashboard.
3. Vercel will instantly generate a live, shareable URL for you.

## 📄 License

This project is open-source and free to use for any personal or celebratory purposes. Have fun and make someone's day!
