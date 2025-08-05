# Shelter Link - Migrant Worker Support Platform

![Shelter Link Logo](https://img.shields.io/badge/Shelter%20Link-Migrant%20Support-blue?style=for-the-badge)

## 🌟 Overview

Shelter Link (also known as MigrantConnect) is a comprehensive digital platform designed to bridge the gap between migrant workers and essential services across states in India. The platform provides a unified interface for workers to access government benefits, find employment opportunities, and connect with employers while maintaining their rights and dignity.

## 🎯 Key Features

### For Migrant Workers

- **Multi-language Support**: Available in 11 Indian languages (English, Hindi, Bengali, Telugu, Tamil, Marathi, Gujarati, Kannada, Malayalam, Punjabi, Odia)
- **Government Benefits Access**: Easy access to food, health, education, and financial benefits
- **Job Search**: Browse and apply for job opportunities posted by verified employers
- **Digital Identity**: Secure profile management with Aadhaar integration
- **Grievance Support**: Report issues and seek help through integrated support system
- **Cross-state Services**: Access benefits while migrating between states

### For Employers

- **Worker Discovery**: Find skilled workers based on location and skills
- **Job Posting**: Post job opportunities with detailed requirements
- **Application Management**: Review and manage job applications
- **Verification System**: Access to verified worker profiles
- **Multi-language Communication**: Communicate in preferred languages

### Blockchain Integration

- **Decentralized Registry**: Workers and employers are registered on blockchain for transparency
- **Smart Contracts**: Secure and immutable record keeping
- **MetaMask Integration**: Web3 wallet connectivity for blockchain interactions
- **Real-time Updates**: Live notifications for new registrations

## 🏗️ Technical Architecture

### Frontend Technologies

- **HTML5**: Semantic markup for accessibility
- **Tailwind CSS**: Modern, responsive UI framework
- **Vanilla JavaScript**: Core functionality and interactions
- **Web3 Integration**: Ethers.js for blockchain connectivity

### Blockchain Integration

- **Ethereum Compatible**: Works with Ethereum and compatible networks
- **Smart Contracts**: Solidity-based contracts for data management
- **MetaMask**: Browser wallet integration
- **Event Listening**: Real-time blockchain event monitoring

### Key Components

- **Language System**: Dynamic translation system supporting 11 languages
- **Authentication**: Local storage-based session management
- **Responsive Design**: Mobile-first approach for accessibility
- **Offline Support**: Progressive Web App features

## 📁 Project Structure

```
hackathon/
├── index.html                 # Main login page
├── dashboard.html             # Worker dashboard
├── employer-dashboard.html    # Employer dashboard
├── register.html             # Registration page
├── qr.html                   # QR code generation
├── jobs.html                 # Job listings
├── grievances.html           # Grievance management
├── food.html                 # Food benefit services
├── health.html               # Healthcare services
├── education.html            # Education services
├── finance.html              # Financial services
├── welfare.html              # Welfare schemes
├── assets/
│   ├── css/
│   │   └── tailwind-styles.css    # Custom styles
│   ├── js/
│   │   ├── main.js               # Core functionality
│   │   ├── language.js           # Translation system
│   │   ├── jobs.js               # Job-related functions
│   │   ├── grievances.js         # Grievance handling
│   │   ├── welfare.js            # Welfare schemes
│   │   └── qrcode.min.js         # QR code generation
│   └── lang/
│       ├── en.json               # English translations
│       ├── hi.json               # Hindi translations
│       ├── bn.json               # Bengali translations
│       ├── te.json               # Telugu translations
│       ├── ta.json               # Tamil translations
│       ├── mr.json               # Marathi translations
│       ├── gu.json               # Gujarati translations
│       ├── kn.json               # Kannada translations
│       ├── ml.json               # Malayalam translations
│       ├── pa.json               # Punjabi translations
│       └── or.json               # Odia translations
├── SHELTER-LINK-PRESENTATION-SUMMARY.md
├── WEBSITE-DEVELOPMENT-FLOWCHART.md
└── README.md                 # This file
```

## 🚀 Getting Started

### Prerequisites

Before running this project locally, ensure you have:

1. **Web Browser**: Modern browser (Chrome, Firefox, Safari, Edge)
2. **MetaMask Extension**: For blockchain features (optional)
3. **Local Web Server**: One of the following:
   - Python (comes with most systems)
   - Node.js with live-server
   - XAMPP/WAMP/MAMP
   - VS Code with Live Server extension

### Installation & Setup

#### Method 1: Using Python (Recommended)

1. **Clone or Download the Project**

   ```bash
   git clone https://github.com/Ishant-Modi/Shelter-Link.git
   cd Shelter-Link
   ```

   Or download and extract the ZIP file.

2. **Navigate to Project Directory**

   ```bash
   cd hackathon
   ```

3. **Start Local Server**

   For Python 3:

   ```bash
   python -m http.server 8000
   ```

   For Python 2:

   ```bash
   python -m SimpleHTTPServer 8000
   ```

4. **Open in Browser**
   ```
   http://localhost:8000
   ```

#### Method 2: Using Node.js

1. **Install Node.js** from [nodejs.org](https://nodejs.org/)

2. **Install live-server globally**

   ```bash
   npm install -g live-server
   ```

3. **Navigate to project directory and start server**
   ```bash
   cd hackathon
   live-server
   ```

#### Method 3: Using VS Code Live Server

1. **Install VS Code** from [code.visualstudio.com](https://code.visualstudio.com/)

2. **Install Live Server Extension**

   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "Live Server"
   - Install by Ritwick Dey

3. **Open Project**
   - Open the `hackathon` folder in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"

#### Method 4: Using XAMPP/WAMP

1. **Install XAMPP** from [apachefriends.org](https://www.apachefriends.org/)

2. **Copy project files**

   - Copy the `hackathon` folder to `xampp/htdocs/`

3. **Start Apache server** from XAMPP control panel

4. **Access in browser**
   ```
   http://localhost/hackathon
   ```

## 🔧 Configuration

### Blockchain Setup (Optional)

To use blockchain features:

1. **Install MetaMask**

   - Add MetaMask extension to your browser
   - Create or import a wallet

2. **Network Configuration**

   - The app is configured for Ethereum-compatible networks
   - Contract address: `0xD7ACd2a9FD159E69Bb102A1ca21C9a3e3A5F771B`

3. **Test Accounts**
   - Use test networks like Goerli or Sepolia for development
   - Get test ETH from faucets for transactions

### Language Configuration

The app supports 11 languages out of the box. To add more languages:

1. Create a new JSON file in `assets/lang/` (e.g., `as.json` for Assamese)
2. Follow the structure of existing language files
3. Update the language selector in HTML files

## 👥 User Accounts

### Test Worker Accounts

- **Ravi Kumar**: `ravi_kumar` (Bihar → Delhi)
- **Priya Sharma**: `priya_sharma` (UP → Maharashtra)
- **Amit Das**: `amit_das` (West Bengal → Karnataka)
- **Sunita Devi**: `sunita_devi` (Rajasthan → Gujarat)

### Test Employer Accounts

- **Mumbai Construction Co.**
- **Delhi Textiles Ltd.**
- **Bangalore Tech Solutions**
- **Chennai Manufacturing**

## 🎮 Usage Guide

### For Workers

1. **Login**

   - Visit the homepage
   - Select "Worker" user type
   - Choose a test account and preferred language
   - Click "Login as Worker"

2. **Dashboard Features**

   - View benefit status and usage
   - Access government services
   - Browse job opportunities
   - Update profile information

3. **Services**
   - **Food**: Apply for food benefits and ration cards
   - **Health**: Access healthcare services and insurance
   - **Education**: Enroll in skill development programs
   - **Finance**: Apply for loans and financial assistance

### For Employers

1. **Login**

   - Select "Employer" user type
   - Choose a company account
   - Access employer dashboard

2. **Features**
   - Post job opportunities
   - Review worker applications
   - Manage company profile
   - Access worker database

### Blockchain Features

1. **Connect Wallet**

   - Click "Connect Wallet" button
   - Approve MetaMask connection

2. **View Registrations**
   - Fetch all registered workers
   - View employer registrations
   - Real-time updates for new registrations

## 🔒 Security Features

- **Data Validation**: Client-side input validation
- **Authentication**: Session-based user management
- **Blockchain Security**: Immutable record keeping
- **Privacy Protection**: Sensitive data masking
- **Cross-site Protection**: Secure form handling

## 🌐 Browser Compatibility

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Responsiveness

The platform is fully responsive and optimized for:

- 📱 Mobile phones (320px+)
- 📟 Tablets (768px+)
- 💻 Desktops (1024px+)
- 🖥️ Large screens (1440px+)

## 🛠️ Development

### Adding New Features

1. **New Service Pages**

   - Create HTML file in root directory
   - Add navigation links in dashboard
   - Update language files with new translations

2. **Extending Language Support**

   - Add new language JSON file in `assets/lang/`
   - Update language selectors in all HTML files
   - Follow existing translation key structure

3. **Blockchain Integration**
   - Update smart contract ABI in relevant files
   - Modify contract address if needed
   - Add new contract functions as required

### Code Organization

- **HTML**: Semantic, accessible markup
- **CSS**: Tailwind utility classes with custom styles
- **JavaScript**: Modular functions with clear separation of concerns
- **Assets**: Organized by type (CSS, JS, languages)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is part of a hackathon submission and is available for educational and demonstration purposes.

## 📞 Support

For support and queries:

- **Email**: ishant.modi9@gmail.com
- **Helpline**: soon
- **Website**: soon

## 🏆 Acknowledgments

- Government of India for migrant worker support initiatives
- Blockchain community for Web3 integration examples
- Open source contributors for language translation resources
- Tailwind CSS for the excellent UI framework

---

**Made with ❤️ for migrant workers across India By Ishant, Nidhi, Alokita, Sneha and Rashi**

_Bridging Services Across States_
