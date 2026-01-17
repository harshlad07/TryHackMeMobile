# TryHackMe Mobile App for iPhone 16

## 🚀 What This Is

A mobile-optimized Progressive Web App (PWA) that lets you access the full TryHackMe website directly on your iPhone 16 like a native app!

## ✨ Features

- **Native App Feel**: Runs in full-screen mode without Safari's UI
- **All TryHackMe Features**: Access everything - labs, rooms, learning paths, leaderboards
- **Beautiful Mobile Design**: Custom-designed interface with cybersecurity aesthetics
- **Navigation Controls**: Back, forward, refresh, home, and URL controls
- **Works Offline**: Install once, open anytime (though you'll need internet for TryHackMe content)
- **No App Store Required**: Install directly from Safari

## 📱 How to Install on Your iPhone 16

### Step 1: Upload the Files
1. Upload `tryhackme-mobile.html`, `manifest.json`, and `sw.js` to a web hosting service
   - Options: GitHub Pages (free), Netlify (free), Vercel (free), or any web host
   - Keep all three files in the same directory

### Step 2: Access from Safari
1. Open Safari on your iPhone 16
2. Navigate to where you hosted the file (e.g., `https://yourusername.github.io/tryhackme-mobile.html`)

### Step 3: Install to Home Screen
1. Tap the **Share** button (the square with arrow pointing up) at the bottom
2. Scroll down and tap **"Add to Home Screen"**
3. Edit the name if you want (default: "TryHackMe Mobile")
4. Tap **"Add"** in the top right

### Step 4: Launch!
1. Find the TryHackMe icon on your home screen
2. Tap it to launch in full-screen mode
3. It will load TryHackMe.com in a mobile-optimized view

## 🎮 How to Use

- **Navigation Bar** (bottom):
  - ← Back button
  - → Forward button  
  - ↻ Refresh page
  - 🔗 Show/hide URL bar (to visit different pages)
  - ⌂ Home (returns to tryhackme.com)

- **URL Bar**: 
  - Tap the link icon to show the URL bar
  - Enter any URL and tap GO
  - Perfect for navigating to specific rooms or your dashboard

## 💡 Quick Hosting Guide

### Option 1: GitHub Pages (Recommended - Free)
1. Create a GitHub account at github.com
2. Create a new repository
3. Upload all three files
4. Go to Settings → Pages
5. Select main branch and save
6. Access via `https://yourusername.github.io/repo-name/tryhackme-mobile.html`

### Option 2: Netlify (Easiest - Free)
1. Go to netlify.com
2. Drag and drop all three files
3. Get instant URL
4. Access via the provided Netlify URL

## 🔒 Privacy & Security

- This app simply loads TryHackMe's website in an iframe
- No data is collected or stored by this app
- All your TryHackMe credentials and data remain on TryHackMe's servers
- The app runs entirely on your device

## 🎨 Design Features

- Cybersecurity-themed dark mode interface
- Animated background grid
- Glowing accents and smooth animations
- Optimized for iPhone 16 screen size and notch
- Professional monospace fonts for that hacker aesthetic

## ⚡ Tips

- For best experience, use it in landscape mode for labs
- The app will remember it's been installed after you add it to home screen
- You can use all TryHackMe features exactly as you would in a browser
- Swipe gestures work naturally within the TryHackMe interface

## 🛠 Technical Details

- Built as a Progressive Web App (PWA)
- Uses iframe to embed TryHackMe website
- Service Worker enables offline shell loading
- Manifest file enables home screen installation
- Fully responsive and touch-optimized

---

Enjoy your mobile TryHackMe experience! 🎯🔐
