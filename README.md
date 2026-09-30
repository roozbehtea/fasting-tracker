[README.md](https://github.com/user-attachments/files/24894102/README.md)
# 🕐 Advanced Fasting Tracker

> Also in this repo: **[Campaign Forge](dnd/)**, a D&D campaign builder. See [`dnd/README.md`](dnd/README.md).

A comprehensive, integrated fasting tracker with automatic data logging, real-time metabolic zone tracking, and detailed statistics.

## 🚀 Quick Setup on GitHub Pages

### Method 1: Upload Files Directly
1. Go to your GitHub repository
2. Click "Add file" → "Upload files"
3. Drag and drop ALL files from this folder
4. Click "Commit changes"
5. Go to Settings → Pages → Select "main" branch → Save
6. Your tracker will be live at `https://yourusername.github.io/your-repo-name`

### Method 2: Using Git (If you have Git installed)
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
# Copy all files from this folder into the repository
git add .
git commit -m "Add fasting tracker"
git push
```
Then enable GitHub Pages in Settings → Pages

## ✨ Features

### 📊 Four Powerful Tabs
- **Current Fast**: Live timer with real-time metabolic zone tracking
- **History**: Complete log of all your fasts with detailed information
- **Statistics**: Auto-calculated progress, streaks, and achievements
- **Profile**: Manage your weight, body fat %, and personal information

### 🎯 Key Capabilities
- ✅ Automatic data storage (browser localStorage)
- ✅ Real-time metabolic zone tracking (Anabolic → Catabolic → Fat Burning → Ketosis → Deep Ketosis)
- ✅ Calorie burn estimation based on your BMR
- ✅ Weight and body composition tracking
- ✅ Fasting streaks and achievements
- ✅ Excel export for backup and analysis
- ✅ Add notes during fasts
- ✅ Set custom fasting goals
- ✅ Detailed insights and recommendations

### 🔬 Metabolic Zones Tracked
1. **Anabolic (0-4 hours)**: Digestion and nutrient storage
2. **Catabolic (4-12 hours)**: Glycogen depletion begins
3. **Fat Burning (12-16 hours)**: Shift to fat metabolism
4. **Ketosis (16-24 hours)**: Significant ketone production
5. **Deep Ketosis (24+ hours)**: Peak autophagy and cellular cleanup

## 📱 How to Use

### Starting Your First Fast
1. Open the tracker (click on `index.html` or visit your GitHub Pages URL)
2. Click "🚀 Start New Fast" 
3. The timer begins automatically
4. Watch as you progress through metabolic zones

### During Your Fast
- Monitor real-time progress and zone status
- View personalized insights based on your profile
- Add notes about how you're feeling
- Set or adjust your fasting goal

### Ending Your Fast
- Click "🍴 End Fast"
- Your fast is automatically saved to history
- Statistics update immediately
- View detailed results

### Managing Your Data
- **History Tab**: View all past fasts, see detailed stats
- **Statistics Tab**: Track your progress over time
- **Profile Tab**: Update weight, body fat, and personal info
- **Export to Excel**: Download a complete backup anytime

## 🔒 Privacy & Data

- All data is stored locally in your browser (localStorage)
- Nothing is sent to any server
- Your fasting data stays on your device
- Data is device-specific and browser-specific
- Use Excel export to backup or transfer data

## 📊 Your Current Profile

**Initial Stats** (as configured):
- Weight: 220 lbs
- Height: 5'5"
- Body Fat: 37%
- BMI: 36.6
- Available fat energy: ~81 lbs (~285,000 calories)

You can update these anytime in the Profile tab!

## 🎨 Customization

The tracker is fully self-contained in a single HTML file. You can customize:
- Colors and styling (edit the CSS in the `<style>` section)
- Metabolic zone timings (edit the zone definitions in JavaScript)
- Profile defaults (edit the `defaultProfile` object)
- Add your own insights and recommendations

## 💡 Tips for Success

1. **Stay Hydrated**: Drink water, black coffee, or tea
2. **Electrolytes**: Consider salt, potassium, magnesium on longer fasts
3. **Break Fast Wisely**: Start with small portions, avoid processed foods
4. **Listen to Your Body**: Dizziness or weakness = time to eat
5. **Quality Sleep**: Enhances fat burning and autophagy

## 📈 Tracking Best Practices

- Update your weight regularly in the Profile tab
- Add notes during fasts to track how you feel
- Review statistics weekly to see progress
- Export to Excel monthly for long-term backup
- Set realistic goals and gradually increase duration

## 🛠️ Technical Details

- **Built with**: Pure HTML, CSS, and JavaScript (no dependencies except xlsx library)
- **Storage**: Browser localStorage API
- **Excel Export**: SheetJS (xlsx.js) library via CDN
- **Responsive**: Works on desktop, tablet, and mobile
- **Offline Ready**: Once loaded, works without internet

## 📝 Notes

- First fast starts from January 27, 2026 at 9:30 AM (as configured)
- BMR calculated using Mifflin-St Jeor equation
- Calorie burn estimates are approximations based on basal metabolic rate
- Metabolic zone timings are general guidelines and can vary by individual

## 🐛 Troubleshooting

**Data not saving?**
- Make sure you're not in private/incognito mode
- Check that browser isn't set to clear data on exit

**Lost your data?**
- If you cleared browser data, history is gone
- Use Excel export regularly for backups

**Timer not updating?**
- Refresh the page
- Make sure JavaScript is enabled

**Can't export to Excel?**
- Make sure you have internet connection (loads library from CDN)
- Try a different browser

## 🚀 Future Enhancement Ideas

- Cloud sync across devices
- Mobile app version
- Push notifications for goals
- Integration with fitness trackers
- Meal planning integration
- Community features

## 📄 License

Feel free to use, modify, and share this tracker!

---

**Start your fasting journey today!** 🎯
