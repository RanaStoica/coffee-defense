⚠️ **WARNING**: This project is in test phase for the $GRIND VIBECODE HACKATHON. DO NOT use main-net wallets with this application. Only use test-net wallets specifically created for testing purposes. Note that early versions do not implement Web3 features.

---

# Coffee Defense - Comprehensive Overview of Features and Technologies

## Overview
Coffee Defense is a blockchain tower defense game where players defend their coffee shop against waves of enemies called "Karens." The game integrates blockchain mechanisms, particularly the $GRIND token, and offers various innovative features such as Contamination Zones and Grind mascot integration.

## Gameplay and Mechanics

### Basic Concept
- **Genre**: Tower Defense
- **Theme**: Defending a coffee shop against disgruntled "Karens"
- **Objective**: Prevent enemies from reaching your coffee shop by strategically placing defensive towers

### Main Mechanics
- **Tower Placement**: Different types of towers with unique abilities
    - Barista Tower: Basic attack
    - Espresso Tower: Long range, high damage
    - Cappuccino Tower: Area damage
    - Frappé Tower: Slows down enemies
    - Grind Hamster Tower: Special tower with unique abilities

- **Enemy Waves**: Progressively increasing difficulty
    - Standard Karen
    - Speed Karen
    - Tank Karen (resistant)
    - Flying Karen
    - Boss Karen
    - Group Karen
    - Complaining Karen (special abilities)

- **In-Game Economy**:
    - Game currency earned by eliminating enemies
    - Used to build and upgrade towers
    - Score system based on performance

- **Level System**:
    - Different maps representing various coffee shops
    - Difficulty progression
    - Unlocking new towers and abilities

## Blockchain Integration

### Network
- **Blockchain**: Abstract Chain
- **Test Environment**: Abstract Testnet

### Smart Contracts
- **CoffeeDefenseGame.sol**: Main game contract
- **CoffeeDefenseDeployment.sol**: Deployment management
- **GrindTokenInterface.js**: Interface to interact with the $GRIND token

### Authentication
- Multi-provider Web3 authentication system
- Support for Metamask and other compatible wallets
- Login system via Privy and Abstract Global Wallet

## Cross-Chain Integration and Shadow NFTs

### Shadow NFT System
- **Concept**: Shadow NFTs are representations of NFTs from other blockchains
- **Technical Implementation**: Uses cross-chain oracles and bridges to verify ownership
- **Synchronization**: Automatic updates when original NFT properties change
- **Gas Optimization**: Reduces transaction costs by keeping game actions on Abstract Chain

### The Plague NFT Integration (Ethereum Mainnet)
- **Original NFTs**: The Plague collection on Ethereum mainnet
- **Shadow Representation**: Each Plague NFT has a Shadow counterpart on Abstract Chain
- **Verification Mechanism**: ZK-proof system to verify ownership without revealing wallet details
- **Benefits**: Plague NFT holders receive special units, abilities, and visual customizations
- **Cross-Chain Bridge**: Custom bridge contract for secure asset verification
- **Update Frequency**: Shadow NFTs sync with originals every 24 hours or on-demand

### Wen Utility Multi-Chain Integration
- **Supported Chains**:
    - Ethereum Mainnet
    - Polygon
    - Avalanche
- **NFT Recognition**: System recognizes Wen Utility NFTs across all three chains
- **Chain-Specific Benefits**:
    - Ethereum: Premium coffee shop skins and highest tier bonuses
    - Polygon: Special defensive abilities and medium tier bonuses
    - Avalanche: Unique offensive abilities and specialized towers
- **Cross-Chain Verification**: Multi-signature verification system
- **Interoperability Protocol**: Custom-built protocol for seamless integration
- **Fallback Mechanism**: If one chain is congested, verification falls back to alternative chains

### Technical Implementation
- **Indexing Service**: Custom indexer that monitors NFT events across chains
- **Caching System**: Caches verification results to minimize cross-chain calls
- **Security Measures**:
    - Multi-layered verification
    - Timelock for major changes
    - Circuit breakers for unusual activity
- **Performance Optimization**: Batched verification for multiple NFTs
- **User Experience**: Transparent to users - automatic detection of eligible NFTs in connected wallets

## $GRIND Token and Token Sinks

### $GRIND Token
- **Utility**: Main currency of the ecosystem
- **Origin**: Developed by the Grind The Coin team
- **Integration**: Via GrindTokenInterface.js

### Token Sinks (Consumption Mechanisms)
1.  **Power-ups and Upgrades Purchases**:
    - Double Shot: Doubles tower power
    - Speed Boost: Increases attack speed
    - Money Maker: Doubles money gains
    - Freeze Time: Freezes enemies
    - Instant Cash: Immediate money
    - Permanent upgrades (extra life, starting capital, etc.)

2.  **Burning System for Unique Rewards**:
    - Exclusive Grind Hamster Tower
    - Golden skin for towers
    - Automatic collector
    - Permanent Double XP
    - Karen Repellent (slows down all enemies)

3.  **Integration with makingcoffee.com**:
    - Order real coffee with $GRIND tokens
    - Various products (espresso, latte, cappuccino, etc.)

### Obtaining Token
- **Purchase**: Buying $GRIND on the open crypto market and fiat (credit cards).
- **Play to Earn**: Earned while playing the game, depending on whether the project can obtain a grant and inject 100% of those funds into the game to be earned by gamers.
- TBC.

## Grind Mascot Integration

### Six Integration Options
1.  **Guide/Narrator Character**:
    - Interactive dialogue
    - Tutorials and tips
    - Reactions to game events

2.  **Special "Grind Hamster" Tower**:
    - Throws coffee beans at enemies
    - 5-level upgrade system
    - Special abilities (Coffee Rain, Energy Boost)

3.  **In-Game Shop Mascot**:
    - Customized shop interface
    - Specific dialogues during purchases
    - Special offers and promotions

4.  **Special "Supreme Karen" Enemy with Grind**:
    - End-of-level boss with Grind as a "hostage"
    - Phase system with evolving abilities
    - Special reward when Grind escapes

5.  **Companion System**:
    - Follows the player's cursor
    - Automatic resource collection
    - Upgrade and customization system
    - Unlockable outfits and accessories

6.  **"Grind Runner" Mini-Game**:
    - Bonus game accessible from the main menu
    - Runner style with obstacles
    - Rewards usable in the main game

## Plague Units and Contamination Zones

### Plague Units
- **Dual Role**: Appear both as enemies and defensive allies
- **Special Abilities**: Unique attacks and status effects
- **Summoning**: Possibility to summon them to help with defense
- **Connection to Ethereum NFTs**: Enhanced units for The Plague NFT holders
- **Cross-Chain Benefits**: Special abilities unlocked based on original NFT traits

### Contamination Zones
- **Concept**: Special areas on the map
- **Advantages**: Provide bonuses to towers placed inside
    - Damage increase
    - Range increase
    - Attack speed increase
    - Special effects (critical, slowing, etc.)
- **Disadvantages**: Attract stronger enemies
- **Strategy**: Risk/reward balance

## Coffee Shops and NFTs

### Coffee Shops
- **Concept**: Represent the buildings to defend
- **Customization**: Different styles and appearances
- **Progression**: Unlocking new cafes with unique layouts
- **Cross-Chain Representation**: Shadow NFTs of Wen Utility coffee shops

### NFT System
- **Representation**: NFTs correspond to coffee shops
- **Ownership**: Possession of customizable coffee franchises
- **Benefits**: Specific bonuses according to the type of coffee shop
- **Cross-Chain Recognition**: System recognizes NFTs from Ethereum, Polygon, and Avalanche
- **Chain-Specific Bonuses**: Different perks based on the blockchain of the original NFT

## Technologies Used

### Frontend
- **Framework**: Next.js
- **Language**: TypeScript/JavaScript
- **Rendering**: React with JSX/TSX components
- **Styles**: CSS modules and Tailwind CSS
- **Internationalization**: Custom i18n system

### Backend and Blockchain
- **Smart Contracts**: Solidity
- **Web3 Integration**: ethers.js
- **Authentication**: Privy and Abstract Global Wallet
- **API**: RESTful for integration with makingcoffee.com
- **Cross-Chain Communication**:
    - Custom oracle system
    - Chainlink for price feeds
    - LayerZero for cross-chain messaging
    - Axelar for general interoperability

### Cross-Chain Technical Stack
- **Indexing**: The Graph for multi-chain data indexing
- **Verification**: ZK-proofs for ownership verification
- **Bridges**: Custom bridge contracts for asset verification
- **State Synchronization**: Event-driven architecture for state updates
- **Caching Layer**: Redis for high-performance caching of verification results
- **Fallback System**: Multi-chain redundancy for high availability

### Game Engine
- **Rendering**: HTML5 Canvas
- **Physics**: Custom system for collision detection
- **Animation**: Sprite and state system
- **Audio**: HTML5 audio system with sound effects and music

### Development Tools
- **Version Control**: Git
- **Package Manager**: npm/yarn
- **Build System**: Webpack via Next.js
- **Testing**: Jest for unit tests
- **Cross-Chain Testing**: Custom testing framework for multi-chain interactions

## Deployment and Testing

### Local Testing Instructions
- Development environment setup
- Dependencies installation
- Wallet configuration for Abstract Testnet
- Obtaining test tokens
- Launching the development server
- Testing cross-chain functionality with local blockchain nodes

### Deployment
- Website deployment via Vercel or similar
- Smart contracts deployment on Abstract Chain
- Integration with external services (makingcoffee.com)
- Cross-chain bridges and oracles deployment
- Monitoring system for cross-chain operations

## Roadmap and Evolution

### Planned Future Features
- New types of towers and enemies
- Season system with changing themes
- Cooperative multiplayer mode
- Global ranking system
- Time-limited events
- Expanded cross-chain support for additional blockchains

### Future Integrations
- More options for using the $GRIND token
- Ecosystem expansion with other games
- Partnerships with other blockchain projects
- Enhanced cross-chain functionality with emerging L2 solutions

### Coffee Defense Team
- **Project Lead**: Rana Stoica
- **Lead Dev**: Manus AI

---

This document provides a comprehensive overview of the features and technologies of the Coffee Defense game, allowing for a quick understanding of the concept, mechanics, and technical architecture of the project. Note that $GRIND is not developed or deployed by the Coffee Defense Team.
