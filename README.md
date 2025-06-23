# 🚀 WebTimeWise Demo

A fully functional demo of the WebTimeWise digital wellness platform, showcasing all features without requiring the Chrome extension.

## 📱 Demo Features

### Device Selection Interface
- **📊 Overall View** - Combined analytics across all devices
- **🌐 Browser View** - Chrome extension data simulation
- **📱 Mobile View** - Mobile app usage tracking
- **💻 Laptop View** - Desktop app analytics
- **📤 Share Stats** - Public weekly summaries

### Interactive Demo Controls
- **5 Different Scenarios:**
  - 📚 Productive Day (6.5 hours productive)
  - 📱 Social Media Day (5.5 hours social)
  - 🔄 Mixed Usage (balanced)
  - 🎮 Gaming Day (5.5 hours gaming)
  - 💼 Work Day (7.5 hours productive)

### Full Functionality
- ✅ Real-time charts and analytics
- ✅ Goal setting and tracking
- ✅ Focus mode with site blocking
- ✅ Voice AI reviews
- ✅ Multi-language support
- ✅ Responsive design
- ✅ Cross-platform simulation

## 🎮 How to Use

1. **Open the demo:**
   ```
   demo/index.html
   ```

2. **Choose a scenario:**
   - Select from 5 different browsing patterns
   - See how data changes across devices

3. **Explore different views:**
   - Click on any device card to see detailed analytics
   - Test all features without extension dependencies

4. **Test functionality:**
   - Goals and settings
   - Focus mode blocking
   - Voice AI reviews
   - Data sharing

## 📁 File Structure

```
demo/
├── index.html              # Main device selection page
├── overall-view.html       # Combined device analytics
├── browser-view.html       # Browser/extension simulation
├── mobile-view.html        # Mobile app tracking
├── laptop-view.html        # Desktop app analytics
├── share-stats.html        # Public sharing interface
├── chrome-compat-demo.js   # Chrome API compatibility
├── demo-data.js           # Demo scenarios and data
├── popup.css              # Styling
├── popup.js               # Dashboard functionality
├── voiceReview.js         # Voice AI features
├── focus-block.js         # Focus mode
├── lib/
│   └── chart.min.js       # Chart.js library
└── flags/                 # Language flags
```

## 🚀 Deployment

### For Hackathon Submission

1. **Deploy to Netlify:**
   ```bash
   # Push to GitHub
   git add demo/
   git commit -m "Add WebTimeWise demo"
   git push origin main
   
   # Deploy on Netlify
   # Connect GitHub repo
   # Set publish directory to: demo/
   ```

2. **Public URL:**
   ```
   https://your-project-name.netlify.app/
   ```

### Local Testing

```bash
# Start local server
python3 -m http.server 8001

# Open demo
open http://localhost:8001/demo/
```

## 🎯 Perfect for Hackathon

This demo showcases:
- ✅ Cross-platform development
- ✅ AI integration (voice reviews)
- ✅ Real-time data visualization
- ✅ Modern web technologies
- ✅ Productivity and wellness focus
- ✅ Interactive demo experience
- ✅ Built with Bolt.new badge included
- ✅ No extension dependencies

## 🔧 Technical Details

- **Chrome API Compatibility:** Simulates Chrome extension APIs
- **Realistic Data:** 5 different browsing scenarios
- **Responsive Design:** Works on all devices
- **Interactive Charts:** Chart.js integration
- **Local Storage:** Demo data persistence
- **Cross-Browser:** Works in all modern browsers

## 📊 Demo Scenarios

Each scenario provides realistic data for:
- Website usage patterns
- Time spent by category
- Goal progress tracking
- Productivity scoring
- Focus mode effectiveness

The demo provides a complete experience of WebTimeWise without requiring any browser extensions or complex setup! 