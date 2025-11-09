# 🎌 Anime Recommendations

A beautiful, modern web application showcasing popular anime recommendations with detailed information and streaming links. Built with pure HTML and CSS, featuring a sleek dark theme with neon accents.

## ✨ Features

- **Modern UI/UX**: Dark theme with neon blue accents and smooth hover animations
- **Anime Collection**: Features 15+ popular anime series including:
  - Demon Slayer
  - Attack on Titan
  - One Piece
  - Hunter x Hunter
  - Death Note
  - Solo Leveling
  - One Punch Man
  - Naruto: Shippuden
  - Jujutsu Kaisen
  - My Hero Academia
  - 86
  - Kaiju No. 8
  - Black Clover
  - Spy x Family
  - Assassination Classroom

- **Detailed Information**: Each anime page includes:
  - Genre classification
  - Release year
  - Story summary
  - Direct streaming links

- **Responsive Design**: Optimized for various screen sizes
- **Smooth Animations**: Interactive hover effects and transitions
- **Easy Navigation**: Clean, organized layout with intuitive navigation

## 🖥️ How It Works

### Website Overview

The Anime Recommendations website provides an intuitive interface for discovering and exploring popular anime series. Here's how it works:

#### 1. **Homepage Interface**
The main page features a dark, futuristic design with two main sections:
- **Anime Recommendation**: Showcases 9 popular mainstream anime series
- **Some Hidden Gems**: Features 6 lesser-known but highly-rated anime

Each anime is displayed in an interactive card format with:
- High-quality poster image
- Anime title
- Hover effects that scale and glow

#### 2. **User Journey**

```
Homepage (index.html)
    ↓
Click on any anime card
    ↓
Individual Anime Page
    ↓
View Details & Streaming Links
```

#### 3. **Interactive Features**

- **Hover Effects**: Cards scale up and glow when hovered over
- **Smooth Transitions**: All animations use CSS transitions for fluid motion
- **Glassmorphism**: Cards use backdrop blur effects for a modern look
- **Responsive Layout**: Cards automatically adjust to screen size

### Workflow Demonstration

1. **Landing on Homepage**
   - User sees the dark-themed homepage with "Anime Recommendation" title
   - Two sections are visible: main recommendations and hidden gems
   - All anime cards are displayed in a responsive grid

2. **Browsing Anime**
   - User hovers over cards to see interactive effects
   - Cards glow with neon cyan color and scale up slightly
   - Smooth animations provide visual feedback

3. **Viewing Details**
   - Clicking a card navigates to the individual anime page
   - Page displays:
     - Anime title in the navigation
     - Genre and release year
     - Story summary
     - Direct link to watch Episode 1

4. **Navigation**
   - All links use relative paths for seamless navigation
   - Works perfectly on GitHub Pages and local servers
   - No external dependencies required

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with:
  - Flexbox for layout
  - Custom animations and transitions
  - Google Fonts (Jost & Orbitron)
  - Backdrop filters and glassmorphism effects
  - CSS variables for consistent theming

## 📁 Project Structure

```
Anime-Recommendations/
├── index.html                 # Main homepage
├── README.md                  # Project documentation
├── *.html                     # Individual anime pages
├── *.jpeg                     # Anime poster images
└── .github/
    └── workflows/
        └── deploy.yml         # GitHub Pages deployment workflow
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/malaniparv905-dot/Anime-Recommendations.git
```

2. Navigate to the project directory:
```bash
cd Anime-Recommendations
```

3. Open `index.html` in your browser, or use a local server:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using VS Code Live Server:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

## 🌐 Deployment

This project is deployed using **GitHub Pages** and is automatically updated on every push to the main branch.

### Live Demo

Visit the live site at: **https://malaniparv905-dot.github.io/Anime-Recommendations/**

### Manual Deployment

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **Save**

The site will be live at: `https://[your-username].github.io/Anime-Recommendations/`

## 🎨 Design Features

- **Color Scheme**:
  - Background: Deep navy blue (`#05071a`)
  - Accent: Neon cyan (`#00e5ff`)
  - Cards: Semi-transparent with blur effects
  - Text: Light cyan (`#e0f7fa`)

- **Typography**:
  - Headings: Orbitron (futuristic, bold)
  - Body: Jost (clean, modern)

- **Interactive Elements**:
  - Hover effects on anime cards
  - Scale transformations
  - Glowing box shadows
  - Smooth transitions

## 📝 Usage

1. Open the homepage (`index.html`)
2. Browse through the anime recommendations
3. Click on any anime card to view detailed information
4. Use the streaming links provided to watch episodes

## 🔧 Customization

To add a new anime:

1. Create a new HTML file (e.g., `new-anime.html`)
2. Add the anime poster image to the root directory
3. Update `index.html` to include a new service box:
```html
<div class="service-box">
  <img src="./anime-poster.jpeg" alt="Anime Name">
  <a href="./new-anime.html">Anime Name</a>
</div>
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more anime recommendations
- Improve the UI/UX
- Fix bugs or typos
- Add new features

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Parv Malani**
- GitHub: [@malaniparv905-dot](https://github.com/malaniparv905-dot)

## 🙏 Acknowledgments

- Google Fonts for the beautiful typography
- All the anime creators and studios for the amazing content
- The anime community for inspiration

---

⭐ If you like this project, please give it a star!
