# Youtube-Inspired Video Platform

A modern, responsive video platform built with React, Vite, and Tailwind CSS that replicates Youtube's design and functionality.

## Features

- 🎥 **Youtube-style Interface** - Authentic design matching Youtube's layout
- 🌙 **Dark/Light Mode** - Toggle between themes with smooth transitions
- 📱 **Responsive Design** - Works perfectly on all device sizes
- 🔍 **Advanced Search** - Search videos, channels, and descriptions
- 📂 **Category Filtering** - Filter content by categories
- 🎯 **Interactive Elements** - Hover effects, animations, and smooth transitions
- 📋 **Collapsible Sidebar** - Youtube-style navigation sidebar
- ⚡ **Fast Performance** - Built with Vite for optimal speed

## Tech Stack

- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript ES6+** - Modern JavaScript features

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd CardCSSRJS
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
CardCSSRJS/
├── src/
│   ├── components/
│   │   ├── VideoPage.jsx      # Main video platform component
│   │   ├── VideoCard.jsx      # Individual video card component
│   │   └── LoadingSpinner.jsx # Loading animation component
│   ├── App.jsx                # Main app component
│   ├── App.css                # Global styles
│   ├── main.jsx               # React entry point
│   └── index.css              # Tailwind imports
├── index.html                 # HTML template
├── package.json               # Dependencies and scripts
├── vite.config.js            # Vite configuration
├── tailwind.config.js        # Tailwind configuration
└── postcss.config.js         # PostCSS configuration
```

## Features Overview

### Header
- Youtube logo and branding
- Centered search bar with search functionality
- Hamburger menu for sidebar toggle
- Dark/light mode toggle
- User avatar placeholder

### Sidebar
- Collapsible navigation menu
- Youtube-style menu items
- Smooth slide animations
- Responsive behavior

### Video Grid
- Responsive grid layout (1-5 columns based on screen size)
- Youtube-style video cards
- Hover effects and animations
- Duration badges and view counts
- Channel avatars with verification badges

### Search & Filtering
- Real-time search across titles, descriptions, and channels
- Category-based filtering
- Sticky category pills
- Empty state handling

## Customization

### Adding New Videos
Edit the `videos` array in `src/components/VideoPage.jsx`:

```javascript
{
  videoSrc: "https://www.Youtube.com/embed/VIDEO_ID",
  title: "Your Video Title",
  views: 1000000,
  duration: "10:30",
  channelName: "Channel Name",
  uploadTime: "1 day ago",
  verified: true
}
```

### Styling
- Modify `tailwind.config.js` for custom colors and themes
- Edit component styles directly in JSX using Tailwind classes
- Add global styles in `src/App.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is for educational purposes. Youtube is a trademark of Google LLC.