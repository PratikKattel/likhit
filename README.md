# likhit

> **नेपाल ड्राइभिंग लाइसेन्स लिखित परीक्षा तयारी (Nepal Driving License Written Exam Preparation Platform)**

A comprehensive, interactive web-based study and practice system designed for candidates preparing for the official Department of Transport Management (DOTM / यातायात व्यवस्था विभाग) driving license written exam in Nepal.

## 🚀 Features

- **Official DOTM Question Bank**: 500+ practice questions extracted from official DOTM guidelines.
- **Traffic Signs & Signals**: Interactive catalog of regulatory, warning, and informational road signs with crisp SVG graphics.
- **Category Support**: Tailored for Category 'A' (Motorcycle/Scooter/Moped) and Category 'B' (Car/Jeep/Delivery Van).
- **Mock Examination**: Timed mock tests simulating the real exam environment with instant scoring and passing criteria.
- **Bilingual Interface**: Questions and explanations in Nepali and English.
- **Offline Capable & Mobile Responsive**: Designed to work smoothly on mobile devices and desktop browsers.

## 📁 Project Structure

- `index.html` - Main exam practice application interface
- `app.js` & `style.css` - Core quiz engine, timer, scoring, and UI styles
- `traffic_signs.html` - Dedicated traffic signs learning module
- `traffic_app.js` & `traffic_style.css` - Traffic signs interactive viewer & filters
- `questions.json` & `questions.js` - Structured question bank with options and answers
- `signals_data.json` & `signals_data.js` - Traffic signal classifications and descriptions
- `create_signals_svg.py` - Automated SVG generator for traffic signs
- `extract_questions.py` - PDF question extractor for DOTM exam materials
- `images/` - SVG and raster assets for road signs and police traffic signals

## 💻 Getting Started

Clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/PratikKattel/likhit.git
cd likhit
# Open index.html in your browser
```

## 📜 License

MIT License. Open source and free for educational use.
