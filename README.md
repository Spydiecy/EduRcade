# eduRcade

![image](https://github.com/user-attachments/assets/3ca66e53-a537-445f-b60a-9c91b0843e44)

## Play-to-Earn Gaming Platform on educhain

eduRcade is a skill-based competitive gaming platform built on the educhain where players can earn real rewards through mini-games. Inspired by platforms like MPL and Winzo, our platform enables users to compete in simple yet engaging games with entry fees, creating prize pools where winners earn real value in the form of educhain tokens.

## 🎮 Project Overview

eduRcade serves as a trustless intermediary, leveraging educhain for transparent and secure prize distribution. Players convert educhain tokens into platform points, which they use to enter competitive game rooms. After competing in skill-based mini-games, winners receive prize pools (minus a small platform commission).

### Target Audience
- Casual gamers looking for competitive play with real rewards
- Crypto enthusiasts interested in gaming applications
- Mobile gamers familiar with skill-based competition
- educhain community members

## ✨ Key Features

### Point System
- **educhain Token Conversion**: Users deposit educhainBTC which converts to platform points
- **Flexible Denominations**: Various point packages available for different player budgets
- **Quest Rewards**: Points earned through platform engagement and social activities
- **Transparent Exchange Rate**: Clear conversion rates between educhain tokens and platform points

### Game Room Mechanics
- **Public Rooms**: Open to anyone with the required entry fee
- **Private Rooms**: Accessible only with invite code
- **Tournament Rooms**: Special events with larger prize pools
- **Room Creation**: Players can create custom rooms with configurable parameters

### Game Portfolio

#### Initial Games
1. **Flappy Bird Clone**
   - Simple tap/click mechanics to navigate obstacles
   - Increasing difficulty as game progresses
   - Score based on distance traveled

2. **AI Challenge Game**
   - Players attempt to trick AI into saying a specific word
   - Target word generated uniquely for each game
   - 1-minute time limit per player
   - AI judging system determines winner based on closest attempt

#### Future Game Expansion
- Racing games
- Puzzle games
- Card games
- Trivia challenges
- Reaction-time games

### Player Statistics & Leaderboards
- Win/loss record tracking
- Total earnings display
- Games played statistics
- Average score calculations
- Game-specific rankings
- Earnings leaderboards

## 🔧 Technical Architecture

### Frontend
- **Framework**: NextJS for fast, responsive UI
- **Styling**: TailwindCSS for clean, consistent design
- **Game Engine**: Canvas-based implementations for games
- **Responsiveness**: Mobile-first design approach

### Blockchain Integration
- **Authentication**: Privy Wallet for seamless user onboarding
- **Smart Contracts**: Solidity contracts deployed on educhain Testnet/Mainnet
- **On-Chain Elements**:
  - Point balances
  - Game results
  - Prize distributions
  - Player statistics

### Smart Contract Architecture
- **Points Management Contract**: Handles educhain token/point conversion
- **Game Room Contract**: Manages room creation and prize distribution
- **Statistics Contract**: Records player and game statistics

## 💼 Business Model

- **Primary Revenue**: 5-10% commission on game prize pools
- **Secondary Revenue**: Premium features, cosmetics, and tournament entry fees
- **Quest Rewards Sponsorships**: Partnerships with brands for sponsored quests

## 📦 Project Structure

eduRcade follows a modular architecture with clear separation of concerns:

### Frontend Components
- **UI Components**: Reusable interface elements with arcade-style aesthetics
- **Game Modules**: Self-contained game implementations with shared scoring systems
- **User Dashboard**: Profile, statistics, and earnings management
- **Tournament System**: Room creation and matchmaking functionality

### Smart Contracts
- **PointsManager.sol**: Handles token conversion and point balances
- **GameRoom.sol**: Manages competitive rooms and prize distribution
- **StatisticsTracker.sol**: Records player performance and leaderboards

### Integration Layer
- **Wallet Connection**: Seamless Privy integration for walletless onboarding
- **Blockchain Interface**: API for interacting with educhain
- **Data Persistence**: On-chain and off-chain data management

## 👥 Team

### [Tanishq Gupta]
**Founder & Lead Developer**  
Passionate blockchain developer with 19+ hackathon wins globally. Selected among 95 students for UZH Blockchain Summer School 2024. Expert in multi-chain development and Web3 innovation.  
[LinkedIn](https://www.linkedin.com/in/tanishqgupta-tech/) · [Twitter/X](https://x.com/Tanishqistaken)
