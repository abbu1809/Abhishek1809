# 🚀 Interactive Elements Setup Guide

This README contains instructions for setting up all the interactive elements in your GitHub profile.

## 📋 Required Setup

### 1. 🐍 Snake Animation (Already Configured ✅)
The snake animation workflow is already set up and will run automatically.

### 2. 🎵 Spotify Now Playing (Optional)

**Steps:**
1. Fork this repo: [novatorem/novatorem](https://github.com/novatorem/novatorem)
2. Deploy to Vercel
3. Connect your Spotify account
4. Update the URL in README.md with your Vercel deployment URL

### 3. ⏱️ WakaTime Coding Stats (Optional)

**Steps:**
1. Sign up at [WakaTime](https://wakatime.com/)
2. Install WakaTime plugin in VS Code
3. Get your API key from WakaTime dashboard
4. Add secret in GitHub repo:
   - Go to: `Settings → Secrets and variables → Actions`
   - Click "New repository secret"
   - Name: `WAKATIME_API_KEY`
   - Value: Your WakaTime API key
5. The workflow will update automatically every 6 hours

### 4. 📊 Recent Activity (Already Configured ✅)

The GitHub activity workflow is already set up and will update every 30 minutes automatically.

### 5. 🏆 Holopin Badges (Optional)

**Steps:**
1. Sign up at [Holopin](https://holopin.io/)
2. Connect your GitHub account
3. Earn badges by participating in events and completing challenges
4. Your badges will automatically appear on your profile

## 🎯 All Interactive Elements

- ✅ **Snake Animation** - Eats your GitHub contributions
- ✅ **Contribution Heatmap** - Color-coded contribution calendar
- ✅ **Activity Graph** - Visual representation of your coding activity
- ✅ **GitHub Trophies** - Achievements based on your GitHub stats
- ✅ **Streak Stats** - Track your commit streak
- ✅ **Language Stats** - Most used programming languages
- ✅ **Random Dev Quote** - Refreshes on every page load
- ✅ **Random Dev Meme** - Fresh meme on every visit
- ✅ **Random Dev Joke** - Coding humor
- 🔄 **Spotify Now Playing** - Currently playing music (requires setup)
- 🔄 **WakaTime Stats** - Detailed coding time breakdown (requires setup)
- 🔄 **Recent Activity** - Latest GitHub activities (auto-updates)
- 🔄 **Holopin Badges** - Digital badges and achievements (optional)

## 📝 Notes

- Most elements work automatically without any setup
- Optional elements enhance your profile but aren't required
- All statistics update automatically via GitHub Actions
- Images are cached and refresh periodically

## 🔧 Troubleshooting

If any element doesn't show:
1. Ensure the repository name is exactly your GitHub username
2. Repository must be public
3. Wait a few minutes for caches to clear
4. Check GitHub Actions tab for any workflow errors

Happy coding! 🚀
