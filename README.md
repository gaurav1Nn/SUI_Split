# SuiSplit 🚀

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Sui Network](https://img.shields.io/badge/Blockchain-Sui-blue.svg)](https://sui.io/)
[![React](https://img.shields.io/badge/Frontend-React-61dafb.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue.svg)](https://www.typescriptlang.org/)
[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen.svg)](https://sui-finale.vercel.app/)

> *Revolutionizing bill-splitting through blockchain technology on the Sui Network*

**🌐 [Live Demo](https://sui-finale.vercel.app/)** | **📚 [Documentation](https://github.com/yourusername/suisplit/wiki)** | **🐛 [Report Issues](https://github.com/yourusername/suisplit/issues)**

SuiSplit is a cutting-edge decentralized bill-splitting application built on the Sui blockchain that eliminates the friction of tracking IOUs and settling debts. Experience transparent, secure, and instant settlements using cryptocurrency with your friends, roommates, and group members.

## 🎯 Try It Now

**👉 [Launch SuiSplit](https://sui-finale.vercel.app/)**

No installation required! Connect your Sui wallet and start splitting bills instantly.

---

## 🌟 Why SuiSplit?

Traditional bill-splitting apps are limited by centralized systems and manual settlements. SuiSplit leverages the power of blockchain to create a trustless, transparent, and instant settlement experience.

| **Traditional Apps** | **SuiSplit** |
|----------------------|--------------|
| Manual cash settlements | ⚡ Instant crypto settlements |
| Centralized databases | 🔒 Immutable blockchain records |
| Trust-based system | 🛡️ Cryptographically secure |
| Limited to local currencies | 🌍 Global accessibility |
| Opaque transaction history | 📊 Transparent, verifiable records |
| Platform dependency | 🔓 Decentralized ownership |

## ✨ Core Features

### 🔐 **Seamless Wallet Integration**
- One-click connection with Sui wallets
- Secure authentication without passwords
- Support for multiple wallet providers

### 💰 **Real-time Balance Tracking**
- Live updates of all participant balances
- Color-coded status indicators
- Automatic debt calculation and optimization

### ⚡ **Smart Settlement System**
- One-click expense settlement via blockchain
- Automatic transaction verification
- Instant confirmation and updates

### 📊 **Interactive Dashboard**
- Beautiful, responsive interface with smooth animations
- Visual representation of all balances and transactions
- Comprehensive expense overview

### 🔍 **Advanced Filtering & Organization**
- Filter by status: All, Pending, or Settled
- Sort by amount, date, or participant name
- Search functionality for quick access

### 🌍 **Global Accessibility**
- Works anywhere with internet connectivity
- Multi-language support (coming soon)
- Cross-platform compatibility

### 🔒 **Transparent & Secure**
- All participants can verify transaction history
- Immutable blockchain records
- No central point of failure

## 🎯 Perfect For

| **Use Case** | **Description** |
|--------------|-----------------|
| 👥 **Friend Groups** | Restaurant bills, entertainment, social activities |
| 🏠 **Roommates** | Rent, utilities, groceries, household expenses |
| ✈️ **Travel Companions** | Trip costs, accommodations, shared activities |
| 🎉 **Event Organizers** | Group purchases, event expenses, party planning |
| 💎 **Crypto Enthusiasts** | Practical DeFi applications, Web3 adoption |
| 👨‍👩‍👧‍👦 **Families** | Shared expenses, allowances, family trips |

## 🚀 Quick Start Guide

### 🌐 **Option 1: Use the Live App (Recommended)**

1. **Visit** [https://sui-finale.vercel.app/](https://sui-finale.vercel.app/)
2. **Connect** your Sui wallet (install [Sui Wallet Extension](https://chrome.google.com/webstore/detail/sui-wallet/opcgpfmipidbgpenhmajoajpbobppdil) if needed)
3. **Start** splitting bills immediately! 🎉

### 💻 **Option 2: Local Development**

#### Prerequisites
- **Node.js** (v18+ recommended) - [Download](https://nodejs.org/)
- **npm** or **yarn** package manager
- **Sui CLI** - [Installation guide](https://docs.sui.io/build/install)
- **Sui Wallet** browser extension

#### One-Command Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/suisplit.git
cd suisplit

# Setup backend
cd sui_back/backend && npm install && cd ../..

# Setup frontend  
cd sui_back/frontend && npm install && cd ../..

# Build smart contracts (optional for development)
cd move && sui move build && cd ..
```

#### Running Locally
You'll need **2 terminal windows**:

**Terminal 1 - Backend:**
```bash
cd sui_back/backend
npm run dev
# 🚀 Backend runs on http://localhost:5000
```

**Terminal 2 - Frontend:**
```bash
cd sui_back/frontend  
npm run dev
# 🌐 Frontend runs on http://localhost:3000
```

**Access your local app:** http://localhost:3000

## 🏗️ Architecture & Technology

### **Frontend Stack**
- **React 18** with TypeScript for type-safe development
- **Tailwind CSS** for modern, utility-first styling
- **Framer Motion** for smooth animations
- **React Context** for efficient state management
- **Vite** for lightning-fast development

### **Backend Stack**
- **Node.js** with Express.js for RESTful API
- **TypeScript** for enhanced developer experience
- **CORS** enabled for seamless frontend integration
- **Custom middleware** for request handling

### **Blockchain Integration**
- **Sui Network** for high-performance, low-cost transactions
- **@mysten/wallet-kit** for seamless wallet connectivity
- **Custom Smart Contracts** written in Move language
- **Sui TypeScript SDK** for blockchain interactions

### **Development Tools**
- **ESLint & Prettier** for consistent code quality
- **PostCSS** for advanced CSS processing
- **TypeScript** across the entire stack
- **Vite** for optimized build processes

## 📖 Complete Usage Guide

### **Getting Started**

1. **🔌 Connect Your Wallet**
   - Click "Connect Wallet" in the navigation
   - Select your preferred Sui wallet
   - Authorize the connection securely

2. **👀 View Your Dashboard**
   - See all participant balances at a glance
   - Use color-coded indicators for quick status identification
   - Access detailed transaction history

3. **🔍 Filter & Organize**
   - Filter balances: All, Pending, or Settled
   - Sort by various criteria (amount, date, participant)
   - Use search to find specific transactions

4. **💸 Settle Balances**
   - Click the settlement button for any outstanding balance
   - Review transaction details in the popup
   - Confirm payment through your wallet
   - Watch real-time updates as settlements process

### **Advanced Features**

- **Bulk Operations**: Settle multiple balances at once
- **Export Data**: Download transaction history as CSV
- **Notifications**: Get alerts for new expenses and settlements
- **Analytics**: View spending patterns and trends

## 🛠️ Project Structure
suisplit/
├── sui-finale/                  # Frontend (React + Vite)
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   ├── sui/
│   │   ├── types/
│   │   └── utils/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── sui_back/                   # Backend (Express)
│   ├── backend/
│   │   ├── src/
│   │   ├── package.json
│   │   └── .env
│   └── move/                   # Sui smart contracts
│
├── move/                       # (Optional) separate smart contracts
├── docs/                       # Documentation
├── README.md
├── .gitignore
├── package.json
├── tailwind.config.js
├── vite.config.ts
├── tsconfig.json

### **Available Scripts**

#### Frontend Commands
```bash
cd sui_back/frontend

npm run dev          # 🚀 Start development server
npm run build        # 📦 Build for production
npm run preview      # 👀 Preview production build
npm run lint         # 🔍 Code quality check
npm run type-check   # 📝 TypeScript validation
```

#### Backend Commands
```bash
cd sui_back/backend
npm install               
node index.js 
```

#### Smart Contract Commands
```bash
cd move

sui move build       # 🔨 Build contracts
sui move test        # 🧪 Run tests
sui move publish     # 🚀 Deploy to network
```

### **Environment Configuration**

#### Frontend (.env.local)
```env
VITE_SUI_NETWORK=devnet
VITE_API_BASE_URL=http://localhost:5000
VITE_CONTRACT_ADDRESS=your_contract_address
VITE_PACKAGE_ID=your_package_id
```

#### Backend (.env)
```env
PORT=5000
NODE_ENV=development
CORS_ORIGIN=http://localhost:3000
SUI_NETWORK=devnet
JWT_SECRET=your_jwt_secret
```

## 🧪 Testing

### **Comprehensive Test Suite**

```bash
# Frontend Testing
cd sui_back/frontend
npm test                    # Run all tests
npm run test:watch         # Watch mode
npm run test:coverage      # Coverage report

# Backend Testing
cd sui_back/backend
npm test                    # Unit tests
npm run test:integration   # API tests
npm run test:coverage      # Coverage report

# Smart Contract Testing
cd move
sui move test              # Contract tests
sui move test --filter specific_test  # Specific tests
```

### **Test Coverage Goals**
- Frontend: >90% component coverage
- Backend: >85% API endpoint coverage
- Smart Contracts: 100% critical path coverage

## 🚀 Deployment Guide

### **Production Deployment**

The main application is deployed at: **[https://sui-finale.vercel.app/](https://sui-finale.vercel.app/)**

#### **Frontend Deployment (Vercel)**
```bash
cd sui_back/frontend
npm run build

# Deploy with Vercel CLI
npm i -g vercel
vercel --prod
```

#### **Backend Deployment Options**

**Railway:**
```bash
cd sui_back/backend
railway login
railway deploy
```

**Heroku:**
```bash
heroku create suisplit-backend
git subtree push --prefix sui_back/backend heroku main
```

#### **Smart Contract Deployment**
```bash
cd move

# Deploy to Sui Devnet
sui move publish --gas-budget 100000000

# Deploy to Sui Mainnet
sui move publish --gas-budget 100000000 --network mainnet
```

### **Deployment Checklist**
- [ ] Environment variables configured
- [ ] Smart contracts deployed and verified
- [ ] Frontend build optimized
- [ ] Backend API endpoints tested
- [ ] CORS policies configured
- [ ] SSL certificates installed
- [ ] Domain configured
- [ ] Analytics and monitoring setup

## 🤝 Contributing

We welcome contributions from developers of all skill levels! Here's how you can help make SuiSplit better:

### **How to Contribute**

1. **🍴 Fork** the repository
2. **📥 Clone** your fork locally
3. **🔧 Setup** development environment
4. **🌿 Create** a feature branch
5. **✨ Make** your improvements
6. **🧪 Test** thoroughly
7. **📝 Commit** with clear messages
8. **🚀 Push** and create a Pull Request

### **Contribution Areas**

- 🐛 **Bug Fixes**: Help us squash bugs
- ✨ **New Features**: Add exciting functionality
- 📚 **Documentation**: Improve guides and docs
- 🎨 **UI/UX**: Enhance user experience
- 🔧 **Performance**: Optimize code and processes
- 🧪 **Testing**: Increase test coverage
- 🌍 **Translations**: Add language support

### **Development Workflow**

```bash
# Fork and clone
git clone https://github.com/yourusername/suisplit.git
cd suisplit

# Create feature branch
git checkout -b feature/amazing-feature

# Make changes and test
npm run test

# Commit changes
git commit -m "✨ Add amazing feature"

# Push and create PR
git push origin feature/amazing-feature
```

### **Code Standards**
- Follow existing code style and conventions
- Write clear, descriptive commit messages
- Add tests for new features
- Update documentation as needed
- Ensure all checks pass before submitting

## 🗺️ Roadmap

### **✅ Current Version (v1.0)**
- Basic expense splitting functionality
- Sui wallet integration
- Real-time balance tracking
- One-click blockchain settlements
- Responsive web interface

### **🔄 Next Release (v1.1) - Q2 2025**
- 💱 Multi-currency support (USDC, SUI, ETH)
- 📱 Progressive Web App (PWA) capabilities
- 📊 Advanced analytics dashboard
- 🔔 Push notifications system
- 🌐 Multi-language support (Spanish, Chinese, Japanese)
- 📤 Export functionality (PDF, CSV)

### **🚀 Future Plans (v2.0) - Q4 2025**
- 📱 Native mobile applications (iOS/Android)
- 💳 Integration with traditional payment methods
- 🤖 AI-powered expense categorization
- 📅 Recurring expense management
- 🏪 Merchant and business integrations
- 🔐 Enhanced privacy features with zero-knowledge proofs
- 🌉 Cross-chain compatibility

### **🌟 Long-term Vision (v3.0+)**
- 🏛️ DAO governance structure
- 💎 Native token economy
- 🔗 Integration with other DeFi protocols
- 🌍 Global merchant network
- 📈 Investment and savings features

## 📊 Project Statistics

![GitHub stars](https://img.shields.io/github/stars/yourusername/suisplit?style=for-the-badge&logo=github)
![GitHub forks](https://img.shields.io/github/forks/yourusername/suisplit?style=for-the-badge&logo=github)
![GitHub issues](https://img.shields.io/github/issues/yourusername/suisplit?style=for-the-badge&logo=github)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/suisplit?style=for-the-badge&logo=github)

### **Community Stats**
- 🌟 **Stars**: Growing community of developers
- 🍴 **Forks**: Active contribution ecosystem
- 🐛 **Issues**: Responsive issue resolution
- 🔄 **Pull Requests**: Collaborative development

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for complete details.

**Key permissions:**
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use

## 🙏 Acknowledgments

Special thanks to the amazing teams and projects that made SuiSplit possible:

- **🔗 Sui Network Team** - For building an incredible blockchain platform
- **🛠️ @mysten/wallet-kit** - For seamless wallet integration tools
- **⚛️ React Team** - For the robust frontend framework
- **🎨 Tailwind CSS** - For beautiful, utility-first styling
- **🌍 Open Source Community** - For countless tools and libraries
- **👥 Early Contributors** - For shaping SuiSplit's future
- **🧪 Beta Testers** - For valuable feedback and bug reports

## 📞 Support & Community

Join our growing community and get the help you need:

### **Get Help**
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/yourusername/suisplit/issues)
- 💬 **Feature Requests**: [GitHub Discussions](https://github.com/yourusername/suisplit/discussions)
- 📧 **Email Support**: support@suisplit.com
- 📚 **Documentation**: [Wiki](https://github.com/yourusername/suisplit/wiki)

### **Stay Connected**
- 🐦 **Twitter**: [@SuiSplit](https://twitter.com/suisplit) - Latest updates
- 💬 **Discord**: [Join Community](https://discord.gg/suisplit) - Real-time chat
- 📱 **Telegram**: [SuiSplit Channel](https://t.me/suisplit) - News & updates
- 📺 **YouTube**: [SuiSplit Tutorials](https://youtube.com/suisplit) - Video guides

### **For Developers**
- 🔧 **Developer Chat**: [Discord #dev-chat](https://discord.gg/suisplit)
- 📖 **API Documentation**: [docs.suisplit.com](https://docs.suisplit.com)
- 🎥 **Developer Tutorials**: [YouTube Playlist](https://youtube.com/playlist?list=suisplit-dev)

## 🎉 Quick Links

| Link | Description |
|------|-------------|
| 🌐 [**Live Demo**](https://sui-finale.vercel.app/) | Try SuiSplit now |
| 📚 [**Documentation**](https://github.com/yourusername/suisplit/wiki) | Complete guides |
| 🐛 [**Report Issues**](https://github.com/yourusername/suisplit/issues) | Bug reports |
| 💬 [**Discussions**](https://github.com/yourusername/suisplit/discussions) | Community chat |
| 🎯 [**Roadmap**](https://github.com/yourusername/suisplit/projects) | Future plans |
| 🤝 [**Contributing**](https://github.com/yourusername/suisplit/blob/main/CONTRIBUTING.md) | How to help |

---

<div align="center">
  
  ## 🚀 **Ready to revolutionize bill splitting?**
  
  ### **[Launch SuiSplit Now →](https://sui-finale.vercel.app/)**
  
  <p><strong>Made with ❤️ by the SuiSplit Team</strong></p>
  <p><em>Bridging traditional finance with the decentralized future</em></p>
  
  ⭐ **Star this repository if SuiSplit helps you!** ⭐
  
  <p>
    <a href="https://sui-finale.vercel.app/">
      <img src="https://img.shields.io/badge/🚀_Try_SuiSplit-Live_Demo-brightgreen?style=for-the-badge" alt="Try SuiSplit">
    </a>
  </p>
  
</div>
