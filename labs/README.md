# Labs & Interactive Visualizations

This directory contains interactive tools and visualizations to enhance your learning experience.

## 📊 Available Visualizations

### 1. **Interactive Schedule Timeline** - `schedule-timeline.html`
A visual timeline of the entire 5-day program with:
- Color-coded modules by day
- Interactive hover states showing module details
- Progress tracking functionality
- Time estimates for each module
- Direct links to detailed schedule sections

**How to use:**
- Open `schedule-timeline.html` in your browser
- Click on any module to jump to detailed content
- Check off completed modules to track progress
- Export your progress as JSON

### 2. **Daily Progress Tracker** - `progress-tracker.html`
An interactive checklist for tracking your daily progress:
- Checkbox for each module and lab
- Time tracking per module
- Daily completion percentage
- Notes section for each day
- Local storage to persist progress

**How to use:**
- Open `progress-tracker.html` in your browser
- Check off items as you complete them
- Add notes about key learnings
- Progress automatically saves to browser

### 3. **Architecture Explorer** (GitHub Pages)
Interactive visualization of the Enterprise Architecture Guide:
- Clickable architecture diagrams
- Zoom and pan functionality
- Layer-by-layer exploration
- Integration flow animations
- Responsive design for mobile/desktop

**Access at:** `https://[your-username].github.io/entra_id_learning/`

## 🚀 Quick Start

### Local Viewing
Simply open any `.html` file in your web browser:
```bash
# macOS
open labs/schedule-timeline.html

# Linux
xdg-open labs/schedule-timeline.html

# Windows
start labs/schedule-timeline.html
```

### GitHub Pages (for Architecture Explorer)
See the main README for setup instructions.

## 📁 File Structure

```
labs/
├── README.md                      # This file
├── schedule-timeline.html         # Interactive 5-day timeline
├── progress-tracker.html          # Daily progress checklist
├── assets/
│   ├── css/
│   │   ├── timeline.css          # Timeline styles
│   │   └── tracker.css           # Tracker styles
│   └── js/
│       ├── timeline.js           # Timeline functionality
│       └── tracker.js            # Tracker functionality
└── data/
    └── schedule-data.json        # Structured schedule data
```

## 🛠️ Customization

All visualizations are built with vanilla HTML/CSS/JavaScript - no build process required!

**To customize:**
1. Edit the HTML files directly
2. Modify CSS in the `assets/css/` directory
3. Update JavaScript in `assets/js/` directory
4. Adjust data in `data/schedule-data.json`

## 💡 Future Enhancements

Ideas for additional visualizations:
- [ ] Gantt chart view of the learning schedule
- [ ] Knowledge map showing concept dependencies
- [ ] Interactive quiz generator per module
- [ ] Flashcard system for key terms
- [ ] Lab environment setup checker
- [ ] Resource bookmarking tool
- [ ] Study time analytics dashboard

## 🤝 Contributing

Have ideas for new visualizations? Feel free to:
1. Create new HTML/JS visualizations
2. Enhance existing tools
3. Add new features to the progress tracker
4. Improve mobile responsiveness

## 📝 Notes

- All tools work offline (no external dependencies beyond CDN links)
- Progress is saved locally in browser (not synced across devices)
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
