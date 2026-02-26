# My Asset Tracker v1.2 (PWA)

A personal asset and portfolio tracker with multi-currency support, now as a Progressive Web App!

## 🎯 What's New in v1.2 (PWA)

- **Reliable Data Storage**: Uses IndexedDB instead of localStorage - your data won't disappear!
- **Install as App**: Works like a native app on phone and desktop
- **Offline Support**: Works without internet connection
- **Auto-updates**: Service worker keeps the app updated
- **No more localStorage confusion**: Each installation has its own persistent data

## 📱 Installation Instructions

### On Desktop (Chrome, Edge, Brave):
1. Open `index.html` in your browser
2. Look for the **"📱 Install App"** button (appears after 3 seconds)
   - OR click the install icon in the address bar
3. Click "Install"
4. App opens in its own window!

### On iPhone/iPad:
1. Open `index.html` in **Safari**
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap "Add"
5. App appears on your home screen!

### On Android:
1. Open `index.html` in **Chrome**
2. Tap the **menu** (three dots)
3. Tap **"Add to Home Screen"** or **"Install app"**
4. Tap "Install"
5. App appears in your app drawer!

## 📁 Files Included

- `index.html` - The main app (open this file)
- `manifest.json` - App configuration
- `service-worker.js` - Offline support & caching

**Important**: Keep all 3 files in the same folder!

## 🌐 Hosting on GitHub Pages (Optional - for sharing)

To share with others via a URL:

1. Create a GitHub account (free)
2. Create a new repository called `asset-tracker`
3. Upload all 3 files
4. Go to Settings → Pages
5. Enable GitHub Pages
6. Get your URL: `https://[username].github.io/asset-tracker`
7. Share that link!

Anyone who visits can install the app on their device. Their data stays private on their device only.

## 💾 Data Migration

If you have data in v1.0 or v1.1:

1. Open old version
2. Click "💾 Backup Data"
3. Open v1.2 PWA
4. Click "📥 Restore Data"
5. Select your backup file

The app will also automatically migrate from old localStorage on first run.

## ✨ Features

- **Multi-currency support**: USD, GBP, EUR, HKD, AED
- **Asset types**: Bank accounts, brokerages, crypto, real estate, other
- **Holdings management**: Track individual holdings within accounts
- **Banking details**: Account numbers, IBAN, SWIFT codes with copy buttons
- **Annual carry calculation**: Estimate yearly cash flow
- **Backup/Restore**: Export and import your data
- **Export summary**: Generate reports for family/emergency contacts

## 🔒 Privacy

- All data stored **locally on your device only**
- No servers, no accounts, no tracking
- Your financial information never leaves your device
- Perfect for sensitive asset tracking

## 🆘 Troubleshooting

**App won't install?**
- Make sure all 3 files are in the same folder
- Try opening in Chrome or Safari (works best)
- Check that you're not in private/incognito mode

**Lost data?**
- Always keep recent backups!
- Click "💾 Backup Data" regularly
- Data in PWA is persistent but backups are your safety net

**Want to uninstall?**
- Desktop: Right-click app icon → Uninstall
- iPhone: Hold icon → Remove App
- Android: Hold icon → Uninstall

## 📝 Version History

- **v1.2 (PWA)**: Progressive Web App with IndexedDB storage
- **v1.1**: Fixed clipboard copy functionality
- **v1.0**: Banking details, holdings, carry calculation
- **Earlier**: Initial versions with basic asset tracking

## 🚀 Future Features (Coming Soon)

- Hide values option in export
- Direct PDF generation
- More currencies
- Investment performance tracking
- Multi-device sync (optional)

---

**Created with ❤️ for personal finance tracking**
