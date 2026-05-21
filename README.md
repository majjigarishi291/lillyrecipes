# Lilly - AI Recipe Generator

Your AI-powered cooking companion. Turn pantry ingredients into restaurant-worthy meals.

## Features

- **AI Recipe Generation**: Generate detailed recipes based on ingredients you have
- **Multi-Language Support**: English and Telugu languages
- **Detailed Recipe View**: Complete cooking instructions, ingredients, nutrition info, and chef's tips
- **AI Cooking Assistant**: Chat with Lilly for cooking tips and guidance
- **Share & Copy**: Easy sharing and copying of recipes
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Build Tool**: Vite
- **AI API**: Google Gemini 2.5 Flash
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites

- Node.js 16+ installed
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/lilly-ai-recipe-generator.git
cd lilly-ai-recipe-generator
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file with your Gemini API key:
```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

### Development

Run the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Building

Build for production:
```bash
npm run build
```

Preview production build:
```bash
npm run preview
```

## Project Structure

```
.
├── index.html           # Main HTML file
├── main.js              # Main JavaScript logic
├── style.css            # Styling
├── vite.config.js       # Vite configuration
├── package.json         # Project dependencies
├── public/              # Static assets
│   ├── image.png        # Lilly logo
│   └── vite.svg         # Vite logo
└── .github/
    └── workflows/
        └── deploy.yml   # GitHub Pages deployment
```

## How to Deploy to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **+** icon → **New repository**
3. Name it: `lilly-ai-recipe-generator`
4. Choose **Public**
5. Click **Create repository**

### Step 2: Connect Local Repository
In your terminal, run:
```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/lilly-ai-recipe-generator.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/root** folder
5. Click **Save**

The workflow will automatically deploy your site. Your app will be live at:
```
https://YOUR-USERNAME.github.io/lilly-ai-recipe-generator
```

## Features in Detail

### Recipe Generation
- Enter ingredients (e.g., "chicken, rice, garlic")
- AI generates 3 detailed recipes with:
  - Cooking time and difficulty level
  - Complete ingredient lists
  - Step-by-step instructions
  - Nutrition information
  - Chef's tips for perfection

### Language Support
- **English**: Default language with full English recipes
- **Telugu**: Complete Telugu recipe generation with Telugu UI

### AI Cooking Assistant
- Chat with Lilly while cooking
- Get substitute suggestions
- Timer reminders and step-by-step guidance
- Available in both English and Telugu

## Usage

1. **Generate Recipes**:
   - Select language (English or Telugu)
   - Enter ingredients separated by commas
   - Click "Generate" button
   - Browse through the 3 generated recipes

2. **View Recipe Details**:
   - Click on any recipe card
   - See full instructions, nutrition, and tips
   - Share or copy the recipe

3. **Use AI Assistant**:
   - Go to "AI Assistant" section
   - Chat with Lilly for cooking help
   - Get real-time cooking advice

## API Key Setup

This project uses the Google Gemini API. To get your free API key:

1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Click "Get API Key"
3. Create a new API key
4. Add it to your `.env` file

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Built with Vite for fast builds
- Optimized CSS and JavaScript
- Responsive images
- Lazy loading support

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Credits

**Brand**: RishiMajjiga  
**AI Engine**: Google Gemini 2.5 Flash

## Contact & Support

For questions or issues, please open an issue on the GitHub repository.

---

Made with ❤️ by RishiMajjiga
