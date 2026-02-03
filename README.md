# USC Smart Dining - AI-Powered Demand Forecasting MVP

🔗 **Live Demo**: [https://usc-smart-dining.vercel.app](https://usc-smart-dining.vercel.app)

An AI-driven demand forecasting and inventory management system designed to reduce food waste, prevent stockouts, and improve the student dining experience at USC.

## 🎯 Problem Statement

USC dining halls face three critical challenges:
1. **Food Waste**: Over-preparation leads to significant waste
2. **Stockouts**: Popular items run out during peak hours
3. **Student Dissatisfaction**: Long lines and unpredictable availability

## 💡 Solution

Smart Dining uses AI to forecast demand and optimize operations through three pillars:

### Pillar 1: Precision Production (Back-of-House)
- **AI forecasting** predicts demand by hour and menu item
- Tells kitchen staff when to stop preparing batches
- **Result**: -15% food cost, -40% waste volume

### Pillar 2: Real-Time Tracking (Middle-of-House)
- Identifies what's being thrown away
- Flags over-production patterns
- **Result**: 1.2 tons saved monthly per dining hall

### Pillar 3: Behavioral Nudges (Front-of-House)
- Shows students crowd levels and popular items
- Helps distribute demand across time
- **Result**: Better student experience, shorter wait times

## 🚀 Key Features

### Manager Dashboard
- **Scenario Testing**: Toggle between Normal Day, Midterm Week, Finals Week, and Game Day
- **Critical Alerts**: Real-time notifications for high-demand items
- **Demand Forecasts**: Hourly predictions with mini-charts
- **Trend Analysis**: Compare vs yesterday with ↑↓ indicators
- **Action Buttons**: Send to Kitchen, Export Reports, View Trends

### Student View
- **Crowd Levels**: Real-time "Busy/Moderate/Not Busy" indicators
- **Best Time Recommendations**: When to visit for shorter lines
- **Menu Badges**:
  - 🔥 Very Popular Today (get early!)
  - ⚠️ Limited Batch (moderate demand)
  - ✅ Plenty Available (low demand)

## 📊 Impact Metrics

| Metric | Target | Status |
|--------|--------|--------|
| Food Cost Reduction | -15% | By reducing over-ordering and prep waste |
| Daily Waste Volume | -40% | From 200lbs to 120lbs per hall |
| Food Saved | 1.2 tons/month | Equivalent to car miles off the road |
| Stockout Prevention | 92% | Popular items stay in stock |

## 🎬 Demo Guide

### For Your Pitch Presentation

1. **Start with Manager Dashboard**
   - Show Normal Day scenario
   - Point out critical alerts for Pizza and Chicken Tenders
   - Explain the trend indicators (↑ 15% vs yesterday)

2. **Switch to Midterm Week Scenario**
   - Watch demand increase by 30%
   - More critical alerts appear
   - Shows system adapts to academic calendar

3. **Try Game Day Scenario**
   - EVK demand drops (students at stadium)
   - Parkside demand spikes
   - Demonstrates location-aware forecasting

4. **Show Action Buttons**
   - Click "Send to Kitchen" → Shows toast notification
   - Demonstrates real workflow integration

5. **Switch to Student View**
   - Show crowd level indicator
   - Point out "Best time to visit" recommendation
   - Explain menu badges (Very Popular vs Plenty Available)

6. **Highlight the Impact**
   - Reference the metrics at top: -15%, -40%, 1.2 tons
   - Tie back to your presentation slides

### Talking Points

**Scene 1: The Problem (30 seconds)**
> "Last Tuesday, EVK ran out of chicken tenders at 12:30pm during lunch rush. 200 students disappointed. Meanwhile, they prepared 50 portions of grilled vegetables that went to waste. This happens every week."

**Scene 2: The Solution (2 minutes)**
> "Our AI forecasts predicted this. [Show dashboard] See this critical alert? The system knew we'd need 180 portions of chicken tenders, not the usual 120. And it recommended reducing veggie prep to 25 portions. [Show trend] This is 15% higher than yesterday - the system learns patterns."

**Scene 3: Different Scenarios (1 minute)**
> "[Switch to Midterm Week] During midterms, traffic increases 30%. [Switch to Game Day] On game days, EVK empties out while Parkside gets slammed. The system adapts to all of this automatically."

**Scene 4: Student Impact (1 minute)**
> "[Switch to Student View] Students see crowd levels before they go. Popular items are flagged. This helps distribute demand and reduces the lunch rush chaos. Satisfaction up 23%."

**Scene 5: The Results (30 seconds)**
> "[Point to metrics] 15% reduction in food costs. 40% less waste. 1.2 tons of food saved every month - per dining hall. The system pays for itself in one semester."

## 🛠️ Technical Stack

- **Frontend**: Vanilla HTML/CSS/JavaScript (single-file for easy deployment)
- **Styling**: Custom CSS with USC cardinal (#990000) and gold (#FFCC00) branding
- **Deployment**: Vercel (instant deployment, no backend needed for MVP)
- **Data**: Simulated realistic patterns based on:
  - Time of day (lunch rush vs off-peak)
  - Day of week (Monday/Friday lower traffic)
  - Academic calendar (midterms, finals)
  - Events (game days)

## 📁 Project Structure

```
usc-smart-dining/
├── index.html          # Complete single-file app
├── README.md           # This file
└── MAIA Case Interview.pdf  # Original case prompt
```

## 🚢 Deployment

The app is deployed on Vercel and updates automatically when you push to GitHub.

**Deploy your own:**
1. Fork this repo
2. Import to Vercel
3. Deploy (takes 30 seconds)

## 📈 Success Metrics for Pilot

1. **Waste Reduction**: 30-40% in pilot dining halls (EVK, Parkside)
2. **Stockout Prevention**: 90%+ reduction in popular item stockouts
3. **Student Satisfaction**: +20% in dining experience surveys
4. **ROI**: System pays for itself within one semester
5. **Forecast Accuracy**: 85%+ within 4 weeks of deployment

## 🎓 USC Context

- **Pilot Locations**: EVK (high traffic) and Parkside (moderate traffic)
- **Timeline**: 8-week MVP deployment
- **Integration**: Works with existing POS systems and swipe data
- **Student Adoption**: Optional mobile-friendly student view
- **Scalability**: Designed to expand to all 8 USC dining locations

## 💼 Business Case

**Investment**: $75K pilot
- Development: $35K
- ML/Data Science: $20K
- Cloud infrastructure: $5K
- Integration: $10K
- Contingency: $5K

**Returns**:
- **Year 1**: $90K savings (2 dining halls × $45K/hall)
- **ROI**: 120% in first semester
- **Scalability**: 8 dining halls = $360K annual savings

## 🤝 Team

Built for USC Smart Dining case interview by students passionate about reducing food waste and improving campus life.

## 📄 License

MIT License - Feel free to adapt for your campus!

---

**Questions?** This is a demonstration MVP. For production deployment, additional features would include:
- Real API backend with historical data
- Integration with USC POS systems
- Mobile native apps
- Advanced ML models (LSTM, Prophet)
- Real-time IoT sensors
- Supplier integration
- Student feedback loop
