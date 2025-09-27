#  PokeTracker ( Pokemon Cards Explorer )

A modern, responsive web application for exploring Pokemon cards with real-time data integration. Built with React, TypeScript, and modern web technologies to provide an intuitive Pokemon card browsing experience.

![Pokemon Cards Explorer](https://img.shields.io/badge/Pokemon-Cards%20Explorer-blue?style=for-the-badge&logo=pokemon)
![React](https://img.shields.io/badge/React-18.2.0-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.2.2-blue?style=for-the-badge&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-5.2.0-purple?style=for-the-badge&logo=vite)

## 🌟 Features

### 🔍 **Smart Search & Discovery**
- **Real-time Search**: Instant search functionality with debounced input
- **Advanced Filtering**: Filter Pokemon by name, type, and other attributes
- **Responsive Design**: Optimized for mobile and desktop experiences

### 📱 **Modern User Interface**
- **Clean Design**: Intuitive and user-friendly interface
- **Mobile-First**: Responsive design that works on all devices
- **Fast Loading**: Optimized performance with lazy loading

### 🎯 **Core Functionality**
- **Pokemon List View**: Browse through comprehensive Pokemon collections
- **Detailed Cards**: View individual Pokemon with detailed information
- **Context Management**: Efficient state management with React Context
- **Redux Integration**: Advanced state management for complex operations

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pokemon-cards.git
   cd pokemon-cards
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application.

## 🛠️ Tech Stack

### Frontend Framework
- **React 18.2.0** - Modern React with concurrent features
- **TypeScript 5.2.2** - Type-safe development
- **Vite 5.2.0** - Lightning-fast build tool

### State Management
- **Redux Toolkit 2.2.3** - Predictable state container
- **React Redux 9.1.1** - Official React bindings for Redux
- **React Context** - Component-level state management

### Styling & UI
- **Tailwind CSS 3.4.3** - Utility-first CSS framework
- **PostCSS 8.4.38** - CSS post-processor
- **Autoprefixer 10.4.19** - Automatic vendor prefixing

### Routing & Navigation
- **React Router DOM 6.23.0** - Declarative routing for React

### Development Tools
- **ESLint** - Code linting and formatting
- **TypeScript ESLint** - TypeScript-specific linting rules

## 📁 Project Structure

```
poketracker/
├── public/                 # Static assets
├── src/
│   ├── app/               # Redux store configuration
│   ├── assets/            # Images and static files
│   ├── components/        # Reusable UI components
│   │   ├── Card/         # Pokemon card component
│   │   ├── Header/       # Navigation header
│   │   └── MobileWrapper/ # Mobile layout wrapper
│   ├── context/           # React Context providers
│   ├── features/          # Redux feature slices
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # Page components
│   │   ├── Counter/      # Counter demo page
│   │   ├── ListPage/     # Pokemon list view
│   │   └── PokeDetail/   # Pokemon detail view
│   ├── utils/             # Utility functions
│   └── types.d.ts         # TypeScript type definitions
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── vite.config.ts
```

## 🎨 Key Components

### **Card Component**
- Displays Pokemon information in a card format
- Responsive design for different screen sizes
- Interactive elements for user engagement

### **Header Component**
- Navigation bar with Pokemon logo
- Integrated search functionality
- Mobile-optimized layout

### **Search Field**
- Real-time search with debouncing
- Optimized performance for large datasets
- User-friendly search interface

## 🔧 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build

# Code Quality
npm run lint         # Run ESLint
```

## 🌐 API Integration

The application integrates with the Pokemon API to fetch:
- Pokemon list data
- Individual Pokemon details
- Real-time search results
- Image assets and sprites

## 📱 Responsive Design

- **Mobile-First Approach**: Optimized for mobile devices
- **Breakpoint System**: Responsive grid layouts
- **Touch-Friendly**: Optimized for touch interactions
- **Cross-Platform**: Works on all modern browsers

## 🚀 Performance Optimizations

- **Code Splitting**: Lazy loading of components
- **Debounced Search**: Optimized search performance
- **Efficient State Management**: Minimal re-renders
- **Bundle Optimization**: Tree shaking and minification

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- **Pokemon API** - For providing comprehensive Pokemon data
- **React Team** - For the amazing React framework
- **Vite Team** - For the lightning-fast build tool
- **Tailwind CSS** - For the utility-first CSS framework

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Check the documentation
- Contact me on Telegram(@lorine93s)

---

**Made with ❤️ for Pokemon fans everywhere!**

![Pokemon](https://img.shields.io/badge/Pokemon-Gotta%20Catch%20Em%20All-red?style=for-the-badge&logo=pokemon)
