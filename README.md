# ReactArt - Authentication UI

A modern React application featuring a beautiful authentication interface with dynamic styling and form validation.

![ReactArt Logo](src/assets/logo.png)

## 🎨 Overview

ReactArt is a React-based web application that showcases a stylish authentication form with:
- **Real-time form validation** - Input validation with visual feedback
- **Modern UI design** - Gradient backgrounds and smooth animations  
- **Responsive layout** - Works seamlessly across devices
- **React 19** - Built with the latest React features

## ✨ Features

- 📧 **Email validation** - Ensures proper email format
- 🔒 **Password validation** - Minimum 6 character requirement
- 🎯 **Interactive feedback** - Visual indicators for invalid inputs
- 📱 **Responsive design** - Mobile-friendly interface
- 🌈 **Animated background** - Beautiful SVG gradient animation

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd react6
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🛠️ Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint to check code quality

## 🏗️ Project Structure

```
react6/
├── public/                 # Static assets
├── src/
│   ├── assets/            # Images and media files
│   ├── components/        # React components
│   │   ├── AuthInputs.jsx # Authentication form component
│   │   └── Header.jsx     # Header component with logo
│   ├── App.jsx           # Main app component
│   ├── main.jsx          # React entry point
│   └── index.css         # Global styles
├── package.json          # Project dependencies and scripts
├── vite.config.js        # Vite configuration
└── index.html           # HTML template
```

## 🎯 Key Components

### AuthInputs Component
- Handles email and password input
- Implements real-time validation
- Provides visual feedback for invalid inputs
- Manages form submission state

### Header Component
- Displays the ReactArt logo and branding
- Responsive design with centered layout
- Custom typography and styling

## 🎨 Styling

The application uses:
- **CSS custom properties** for consistent theming
- **Flexbox layouts** for responsive design
- **CSS animations** for smooth interactions
- **Mobile-first approach** with media queries

## 🔧 Tech Stack

- **React 19** - Frontend framework
- **Vite** - Build tool and development server
- **ESLint** - Code linting and quality
- **CSS3** - Styling and animations

## 📝 Form Validation Rules

- **Email**: Must contain an '@' symbol
- **Password**: Minimum 6 characters required
- **Visual feedback**: Invalid fields are highlighted in red
- **Real-time validation**: Validation occurs after form submission attempt

## 🌐 Browser Support

This application supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help with the project, please open an issue on GitHub.

---

**Built with ❤️ using React and Vite**