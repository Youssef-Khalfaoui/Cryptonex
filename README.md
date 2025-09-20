# CryptoNex 🚀

A modern, responsive cryptocurrency tracking and analysis platform built with React. CryptoNex provides real-time cryptocurrency data, price charts, currency conversion, and the latest crypto news in an elegant and user-friendly interface.

![CryptoNex Banner](./client/public/Landing.png)

## 🌟 Features

### 📊 **Cryptocurrency Tracking**
- Real-time cryptocurrency prices and market data
- Top cryptocurrencies with market cap, volume, and price changes
- Detailed cryptocurrency information and analytics
- Interactive price charts with multiple timeframes
- Infinite scroll for browsing extensive crypto listings

### 💱 **Currency Exchange**
- Multi-currency support with 60+ world currencies
- Real-time exchange rates
- Currency converter with live conversion rates
- Regional currency grouping (Americas, Europe, Asia-Pacific, etc.)
- Currency search and filtering functionality

### 📰 **News & Updates**
- Latest cryptocurrency and blockchain news
- Category-based news filtering (Bitcoin, Ethereum, DeFi, NFT, etc.)
- Article modal with full content reading
- Infinite scroll news feed
- Search functionality for news articles

### 🎨 **Modern UI/UX**
- Responsive design optimized for all devices
- Dark theme with modern glassmorphism effects
- Smooth animations and transitions
- Interactive carousels and components
- Clean, professional interface

## 🛠️ Technology Stack

### **Frontend**
- **React 19.1.1** - UI library with modern hooks
- **Redux Toolkit** - State management
- **React Router** - Navigation and routing
- **Styled Components** - CSS-in-JS styling
- **Chart.js & React Chart.js 2** - Interactive charts
- **Material-UI** - UI components and icons

### **Additional Libraries**
- **Axios** - HTTP client for API requests
- **React Testing Library** - Component testing
- **Web Vitals** - Performance monitoring

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Youssef-Khalfaoui/Cryptonex.git
   cd CryptoNex
   ```

2. **Install dependencies**
   ```bash
   cd client
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

## 📁 Project Structure

```
CryptoNex/
├── client/
│   ├── public/
│   │   ├── index.html
│   │   ├── favicon.ico
│   │   ├── Landing.png
│   │   └── logo assets/
│   ├── src/
│   │   ├── components/          # React components
│   │   │   ├── Header.jsx       # Navigation header
│   │   │   ├── Home.jsx         # Landing page
│   │   │   ├── Crypto.jsx       # Crypto listings
│   │   │   ├── CryptoDetail.jsx # Individual crypto details
│   │   │   ├── Currency.jsx     # Currency exchange
│   │   │   ├── News.jsx         # News section
│   │   │   ├── Converter.jsx    # Currency converter
│   │   │   ├── PriceChart.jsx   # Price charts
│   │   │   └── ...
│   │   ├── hooks/               # Custom React hooks
│   │   │   ├── useCoinGecko.js  # API integration
│   │   │   ├── useCryptoInfiniteScroll.js
│   │   │   └── ...
│   │   ├── features/            # Redux slices
│   │   │   └── coinGeckoSlice.js
│   │   ├── data/                # Static data
│   │   │   └── worldCurrencies.js
│   │   ├── utils/               # Utility functions
│   │   │   └── currencyFormatter.js
│   │   ├── assets/              # Static assets
│   │   ├── App.js               # Main app component
│   │   └── index.js             # Entry point
│   └── package.json
└── README.md
```

## 🔧 Key Components

### **Header Component**
- Responsive navigation with mobile menu
- Currency selector dropdown
- Smooth scrolling navigation

### **Crypto Component**
- Cryptocurrency listings with infinite scroll
- Sorting functionality (price, market cap, volume)
- Real-time price updates

### **Currency Component**
- World currencies with exchange rates
- Search and filter functionality
- Pagination for large datasets

### **News Component**
- Crypto news with category filtering
- Article modal for full content
- Infinite scroll implementation

### **Chart Component**
- Interactive price charts
- Multiple timeframe support (1D, 7D, 30D, 1Y)
- Chart.js integration with custom styling

## 🎨 Design Features

### **Responsive Design**
- Mobile-first approach
- Breakpoints for tablet and desktop
- Flexible grid layouts

### **Dark Theme**
- Modern dark color scheme
- Glassmorphism effects
- Smooth hover animations

### **Performance Optimizations**
- Lazy loading for images
- Infinite scroll pagination
- Optimized Redux state management
- Code splitting and bundling

## 📊 API Integration

The application integrates with:
- **CoinGecko API** - Cryptocurrency data
- **Exchange Rate API** - Currency conversion rates
- **Mock News API** - Cryptocurrency news (configurable)

## 🧪 Testing

Run the test suite:
```bash
npm test
```

## 📈 Performance

- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices)
- **Bundle Size**: Optimized with code splitting
- **Load Time**: < 3 seconds on standard connections

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Youssef Khalfaoui**
- GitHub: [@Youssef-Khalfaoui](https://github.com/Youssef-Khalfaoui)
- Project Link: [https://github.com/Youssef-Khalfaoui/Cryptonex](https://github.com/Youssef-Khalfaoui/Cryptonex)

## 🙏 Acknowledgments

- [CoinGecko](https://www.coingecko.com/) for cryptocurrency data
- [ExchangeRate-API](https://exchangerate-api.com/) for currency exchange rates
- [React](https://reactjs.org/) team for the amazing framework
- [Chart.js](https://www.chartjs.org/) for interactive charts
- [Styled Components](https://styled-components.com/) for CSS-in-JS styling

## 🔮 Future Enhancements

- [ ] Portfolio tracking functionality
- [ ] Price alerts and notifications
- [ ] Advanced technical analysis tools
- [ ] User authentication and profiles
- [ ] Watchlist management
- [ ] Social features and community integration
- [ ] Mobile app development
- [ ] Real-time WebSocket data updates

---

**⭐ Don't forget to star this repository if you found it helpful!**