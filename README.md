# Phrase Generator

A fun and creative web application that generates random phrases and AI-powered images based on your personal preferences.

## About This Project

This project was created as part of the **GitHub JavaScript Course** from GitHub Education on Scrimba. It takes your personal information (name, favorite activity, favorite place) and uses AI to generate unique phrases and corresponding images. Perfect for creative inspiration or just having some fun!

The original course teaches JavaScript fundamentals and modern web development practices, and this project demonstrates those concepts in action.

## Features

- 🎨 AI-powered phrase generation
- 🖼️ Auto-generated images for each phrase
- 🎯 Customizable personality through temperature settings
- ⚡ Built with Vite for fast development and optimized builds

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm

### Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Usage

1. Update the variables in `index.js` with your personal information:
   - `name`: Your name
   - `favoriteActivity`: Your favorite activity
   - `favoritePlace`: Your favorite place
   - `temperature`: AI creativity level (0-1, where 1 is most random)

2. Optionally, replace `avatar.jpg` with your own photo

3. The app will generate phrases and images based on your preferences!

## Configuration

### Temperature Setting

The `temperature` variable controls how creative and experimental the AI output will be:
- **0**: More consistent, predictable output
- **1**: Maximum creativity and randomness

## Technologies Used

- **Vite**: Next generation frontend tooling
- **JavaScript**: Core application logic
- **CSS**: Styling
- **HTML**: Structure

## Development

For more information about Vite configuration, visit [vitejs.dev](https://vitejs.dev/)

### Available Commands

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
```

## License

This project is open source and available under the MIT License.

---

Happy generating! 🚀
