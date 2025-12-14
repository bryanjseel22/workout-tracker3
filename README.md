# Workout Tracker PWA

A Progressive Web App for tracking workouts, personal records, and progress. All data is stored locally on your device using localStorage.

## Features

- 📱 **Progressive Web App (PWA)** - Install on your phone and use like a native app
- 💾 **Local Storage** - All data saved only on your device (no cloud sync)
- 🏋️ **Exercise Library** - Comprehensive library of exercises organized by muscle groups
- 📊 **Volume Tracking** - Track total volume and volume by muscle group
- 🏆 **Personal Records** - Automatically track and celebrate PRs
- 🧮 **Plate Calculator** - Calculate plate loading for barbells, dumbbells, and machines
- 📈 **Weekly Stats** - View weekly volume by muscle group
- 📝 **Workout History** - Review past workouts with full details

## Deployment to Vercel

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Vercel will automatically detect and deploy
   - No build step needed - it's a static site!

3. **Access on Your Phone**
   - Open the deployed URL on your phone's browser
   - Look for "Add to Home Screen" option
   - The app will work offline after first load

## Local Development

Simply open `index.html` in a browser. No build step required!

## Data Storage

All workout data is stored in your browser's localStorage:
- `workout-history` - All completed workouts
- `personal-records` - Your PRs for each exercise

**Note:** Data is device-specific and not synced across devices or backed up to the cloud.

## Browser Support

Works on all modern browsers that support:
- React 18
- localStorage
- Service Workers (for PWA features)

## Mobile Installation

### iOS (Safari)
1. Open the app in Safari
2. Tap the Share button
3. Select "Add to Home Screen"

### Android (Chrome)
1. Open the app in Chrome
2. Tap the menu (three dots)
3. Select "Add to Home Screen" or "Install App"

## License

Free to use and modify.

