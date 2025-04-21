⚠️ **WARNING**: This project is in test phase for the $GRIND VIBECODE HACKATHON. DO NOT use main-net wallets with this application. Only use test-net wallets specifically created for testing purposes. Actual implementationWeb3 features will start closer to the submission deadline for Hackathon.

---

# Coffee Defense: A Karen Story

Coffee Defense: A Karen Story is a tower defense game where you protect your coffee shop from "Karen" invaders using various tower types and special abilities. This game features blockchain integration with $KAREN and $GRIND tokens, as well as NFT functionality.

## Features

- **Tower Defense Gameplay**: Place and upgrade different types of coffee-themed towers
- **Enemy Variety**: Different types of "Karen" enemies with unique behaviors
- **Web3 Integration**: Connect your wallet and earn real tokens
- **Grind Hamster Features**:
  - Special Hamster Tower (purchasable with $GRIND tokens)
  - Grind Runner Mini-Game
  - Interactive Guide/Narrator

## Local Testing Setup

Follow these steps to run the game locally:

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Basic understanding of running a local web server
- Optional: MetaMask or another Web3 wallet for blockchain features

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/coffee-defense.git
   cd coffee-defense
   ```

2. Start a local web server. You can use any of these methods:

   **Using Python:**
   ```
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

   **Using Node.js:**
   ```
   # Install http-server globally (if not already installed)
   npm install -g http-server
   
   # Start server
   http-server
   ```

3. Open your browser and navigate to:
   - http://localhost:8000 (if using Python)
   - http://localhost:8080 (if using http-server with default settings)

### File Structure

```
coffee-defense/
  ├── index.html           # Main HTML entry point
  ├── README.md            # This file
  ├── js/
  │   ├── coffee-defense-core.js    # Core game engine
  │   ├── blockchain-config.js      # Blockchain settings
  │   ├── karen-token-system.js     # $KAREN token functionality
  │   ├── hamster-tower.js          # Grind Hamster Tower
  │   ├── grind-runner-minigame.js  # Grind Runner mini-game
  │   ├── grind-hamster-guide.js    # In-game tutorial guide
  │   └── main.js                   # Main initialization
  └── assets/
      └── placeholder.txt          # Placeholder for future assets
```

## Blockchain Integration

The game integrates with the following blockchain components:

- **$KAREN Token**: Main in-game currency (deployed on Abstract testnet)
- **$GRIND Token**: Special currency for premium features
- **WEN Utility NFTs**: Provides in-game bonuses
- **The Plague NFTs**: Can be used as support units or enemies

### Test Environment

For local testing, the game includes mock implementations of Web3 functionality that simulate blockchain interactions without requiring actual tokens or connections.

## Game Controls

- **Tower Placement**: Select a tower type and click on the map to place it
- **Tower Info**: Click on a placed tower to view stats and upgrade options
- **Wave Control**: Use the Start Wave button to begin enemy waves
- **Speed Control**: Adjust game speed for faster gameplay
- **Abilities**: Use special abilities like "Karen Repellent" during tough waves

## Development Notes

- The mock Web3 implementation allows testing without blockchain connections
- For full functionality, connect a Web3 wallet containing the appropriate tokens/NFTs
- All contract addresses are configurable in `blockchain-config.js`

## License

MIT License - See LICENSE file for details.

### Coffee Defense: A Karen Story Team
- **Project Lead**: Rana Stoica - contact@ranastoica.xyz
- **Lead Dev**: Claude AI
- **Dev Assistants**: Manus AI, Gemini AI 2.5 Pro & ChatGPT o3

For questions or support, please open an issue on this repository.
