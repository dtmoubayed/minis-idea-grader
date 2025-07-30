# 🚀 Mini Idea Grader

A web application for evaluating Shop App Mini ideas against the official criteria. Users can submit their Mini concepts and receive instant feedback with grades (A-F) and detailed analysis.

## 🌐 Live Demo

**[Try the Mini Idea Grader →](https://yourusername.github.io/mini-idea-grader)**

*(Replace with your actual GitHub Pages URL after deployment)*

## ✨ Features

- **Interactive grading system** with A-F scoring
- **Real-time analysis** against three key criteria:
  - Leverages Shop's Catalog
  - Provides Personalization 
  - Creates Habits
- **Detailed feedback** showing which criteria are met/not met
- **Example Mini ideas** for inspiration
- **Responsive design** that works on all devices
- **No backend required** - runs entirely in the browser

## 🚀 Quick Deploy to GitHub Pages

### Option 1: Fork This Repository (Easiest)

1. **Fork this repository** by clicking the "Fork" button at the top right
2. **Go to your forked repository settings**
3. **Scroll down to "Pages" section**
4. **Set Source to "Deploy from a branch"**
5. **Select "main" branch and "/ (root)" folder**
6. **Click Save**
7. **Your site will be available at `https://yourusername.github.io/mini-idea-grader`**

### Option 2: Create New Repository

1. **Create a new GitHub repository** named `mini-idea-grader`
2. **Clone your repository locally:**
   ```bash
   git clone https://github.com/yourusername/mini-idea-grader.git
   cd mini-idea-grader
   ```
3. **Copy the `index.html` file** into your repository
4. **Commit and push:**
   ```bash
   git add .
   git commit -m "Add Mini Idea Grader"
   git push origin main
   ```
5. **Enable GitHub Pages** in repository settings (same as Option 1, steps 3-7)

## 📋 How It Works

### Evaluation Criteria

The grader analyzes Mini ideas based on three core attributes that make great Minis:

#### 1. Leverages Shop's Catalog 🏪
- Works across Shop's expansive catalog of products and merchants
- Uses product metadata effectively
- **Keywords detected:** catalog, products, merchandise, brands, shopping, etc.

#### 2. Provides Personalization 👤
- Leverages user identity data and preferences
- Creates tailored experiences based on purchase history
- **Keywords detected:** personalized, preferences, favorites, recommendations, etc.

#### 3. Creates Habits 🔄
- Gives users reasons to return daily
- Includes social features and engagement loops
- **Keywords detected:** daily, social, share, community, habits, etc.

### Grading Scale

- **A Grade:** Meets all 3 criteria strongly (excellent Mini idea)
- **B Grade:** Meets all 3 criteria or 2 criteria very well
- **C Grade:** Meets 2 criteria or 1 criteria well
- **D Grade:** Meets 1 criteria or has some potential
- **F Grade:** Doesn't align with Mini criteria

## 🎯 Example Mini Ideas

### Great Examples (A/B Grade)
- **Social AR Try-On:** "Users can try on clothes using AR, save favorites to their profile, and share outfit posts with friends for likes and comments"
- **Daily Style Challenge:** "Daily outfit challenges based on user's purchase history and preferences, with leaderboards and social sharing"
- **Personalized Product Hunt:** "AI-curated daily product recommendations based on browsing history, with social voting and habit streaks"

### Needs Improvement (C/D/F Grade)
- **Generic Calculator:** "A simple tip calculator" (no catalog, personalization, or habits)
- **One-time Tool:** "Check if a product is in stock" (one-time use, no retention)
- **Basic Info:** "Show store hours" (informational only)

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - no framework dependencies
- **Client-side only** - no server required
- **Responsive design** with modern CSS Grid/Flexbox
- **Keyword analysis** with scoring algorithm
- **Mobile-friendly** interface

## 🎨 Customization

You can easily customize the grader by modifying:

- **Keywords and scoring** in the `criteria` array
- **Grading thresholds** in the `calculateGrade()` function
- **Styling** via CSS variables and classes
- **Example Mini ideas** in the examples section

## 📱 Mobile Support

The grader is fully responsive and works great on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🤝 Contributing

Feel free to submit issues and pull requests to improve the Mini Idea Grader!

### Ideas for Enhancement
- AI-powered analysis using language models
- Integration with Shop API for real product data
- User accounts and idea saving
- Community voting on Mini ideas
- Advanced NLP analysis

## 📄 License

MIT License - feel free to use this for your own projects!

---

**Built for the Shop App Mini ecosystem** 🛍️ 