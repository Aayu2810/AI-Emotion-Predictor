# 🧠 AI Emotion Predictor

<div align="center">

![Emotion Predictor Banner](https://img.shields.io/badge/AI-Emotion%20Predictor-blueviolet?style=for-the-badge&logo=brain&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🎯 Understand Emotions in Any Text

*An advanced sentiment analysis tool that predicts emotions, analyzes tone, and provides psychological insights from text using AI-powered algorithms.*

[🚀 Live Demo](https://aayu2810.github.io/AI-Emotion-Predictor/) • [📖 Documentation](#features) • [🐛 Report Bug](https://github.com/aayu2810/AI-Emotion-Predictor/issues)

</div>

---

## 🌟 Overview

AI Emotion Predictor is a sophisticated web application that analyzes text to detect emotions, sentiment, and psychological patterns. Built entirely in JavaScript, it runs 100% in your browser with no external API calls required - ensuring complete privacy and instant results.

### ✨ What Makes It Special?

- 🎭 **Multi-Emotion Detection** - Identifies 8+ distinct emotions with confidence scores
- 📊 **Advanced Sentiment Analysis** - Scores from -100 (very negative) to +100 (very positive)
- 🧪 **Psychological Insights** - Generates meaningful analysis about the writer's mental state
- 🔒 **100% Private** - All processing happens locally in your browser
- ⚡ **Instant Results** - Get comprehensive analysis in under 2 seconds
- 💯 **No API Keys** - No sign-up, no configuration, just works!

---

## 🎬 Demo

> **Try it live:** [https://aayu2810.github.io/AI-Emotion-Predictor/](https://aayu2810.github.io/AI-Emotion-Predictor/)

---

## 🚀 Features

### Core Capabilities

| Feature | Description |
|---------|-------------|
| 🎭 **Primary Emotion Detection** | Identifies the dominant emotion: joy, sadness, anger, fear, surprise, disgust, love, excitement |
| 📈 **Emotion Intensity** | Measures how strongly the emotion is expressed (0-100%) |
| 💬 **Sentiment Scoring** | Quantifies overall positivity/negativity with precise scoring |
| 🔄 **Secondary Emotions** | Detects multiple emotions present in the text |
| 🎯 **Theme Identification** | Extracts key themes like career, family, relationships, health |
| 🎨 **Tone Analysis** | Describes the overall writing style and mood |
| 🧠 **Psychological Insights** | Provides meaningful analysis of the writer's state of mind |
| 📝 **History Tracking** | Keeps track of recent analyses for pattern recognition |

### Technical Features

- ✅ **Lexicon-Based Analysis** - 100+ emotion keywords
- ✅ **Context-Aware Processing** - Handles intensifiers and negations
- ✅ **Real-Time Processing** - No server delays
- ✅ **Responsive Design** - Works on desktop, tablet, and mobile
- ✅ **Glassmorphic UI** - Modern, beautiful interface
- ✅ **Dark Mode** - Easy on the eyes

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=flat-square) | Component-based UI framework |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) | Core programming language |
| ![TailwindCSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white&style=flat-square) | Utility-first CSS framework |
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) | Markup structure |
| ![Lucide](https://img.shields.io/badge/-Lucide-F56565?logo=feather&logoColor=white&style=flat-square) | Beautiful SVG icons |

</div>

---

## 📦 Installation & Setup

### Quick Start (No Installation Required!)

Simply visit the live demo: [https://aayu2810.github.io/AI-Emotion-Predictor/](https://aayu2810.github.io/AI-Emotion-Predictor/)

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/aayu2810/AI-Emotion-Predictor.git
cd AI-Emotion-Predictor
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

No build steps, no dependencies, no configuration needed! 🎉

---

## 💡 Usage

### Basic Usage

1. Visit the app
2. Enter or paste any text in the input field
3. Click "Analyze Emotions"
4. View comprehensive emotional analysis instantly

### Example Use Cases

#### 📝 Content Creation
Analyze blog posts, social media content, or marketing copy to ensure the right emotional tone.

```
Input: "I'm absolutely thrilled to announce our new product launch! 
       This has been months in the making and I couldn't be happier."

Output:
- Primary Emotion: Joy (95% confidence)
- Sentiment: Very Positive (+85)
- Themes: Career, Achievement
```

#### 💼 Customer Feedback Analysis
Quickly gauge sentiment in customer reviews and support tickets.

```
Input: "This service is terrible. I've been waiting for 3 days with no response!"

Output:
- Primary Emotion: Anger (88% confidence)
- Sentiment: Very Negative (-75)
- Themes: Customer Service, Frustration
```

#### 🧠 Journal Analysis
Track emotional patterns in personal writing over time.

```
Input: "Today felt overwhelming. Too many deadlines, not enough time."

Output:
- Primary Emotion: Fear/Anxiety (82% confidence)
- Sentiment: Negative (-45)
- Themes: Work, Stress
```

---

## 🧪 How It Works

### Algorithm Overview

```javascript
1. Text Preprocessing
   ↓
2. Tokenization & Cleaning
   ↓
3. Emotion Detection (Lexicon-Based)
   ↓
4. Sentiment Scoring (Positive/Negative Words)
   ↓
5. Intensity Calculation (Intensifiers Detection)
   ↓
6. Theme Extraction (Keyword Matching)
   ↓
7. Psychological Analysis (Rule-Based)
```

### Key Components

- **Emotion Lexicon**: 100+ words mapped to 8 core emotions
- **Sentiment Dictionary**: Positive and negative word lists
- **Intensifier Detection**: Identifies amplifying words (very, extremely, etc.)
- **Pattern Recognition**: Detects common themes and topics

---

## 🎯 Roadmap

- [x] Basic emotion detection
- [x] Sentiment analysis
- [x] Theme identification
- [x] Beautiful UI with animations
- [x] History tracking
- [ ] Export results as PDF/JSON
- [ ] Batch text analysis
- [ ] Emotion trends visualization
- [ ] Support for multiple languages
- [ ] Advanced NLP integration
- [ ] Chrome extension

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎉 Open a Pull Request

### Areas for Contribution

- 🐛 Bug fixes
- ✨ New features
- 📝 Documentation improvements
- 🎨 UI/UX enhancements
- 🌍 Translations

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

<div align="center">

### **AAYUSHI PRIYA**

[![GitHub](https://img.shields.io/badge/GitHub-aayu2810-181717?style=for-the-badge&logo=github)](https://github.com/aayu2810)

*Passionate about AI, Web Development, and creating tools that make a difference.*

</div>

---

## 🙏 Acknowledgments

- Inspired by the need for accessible emotional intelligence tools
- Built with modern web technologies
- Icons by [Lucide](https://lucide.dev/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)

---

## 📊 Project Stats

![GitHub Stars](https://img.shields.io/github/stars/aayu2810/AI-Emotion-Predictor?style=social)
![GitHub Forks](https://img.shields.io/github/forks/aayu2810/AI-Emotion-Predictor?style=social)
![GitHub Issues](https://img.shields.io/github/issues/aayu2810/AI-Emotion-Predictor)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/aayu2810/AI-Emotion-Predictor)

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ by Aayushi Priya**

[⬆ Back to Top](#-ai-emotion-predictor)

</div>
