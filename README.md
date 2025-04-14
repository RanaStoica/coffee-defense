# Coffee Defense

A tower defense game where you defend your coffee shop against waves of angry "Karens", with integration of the $GRIND token on Abstract Chain.

## About the Project

Coffee Defense is a tower defense game developed for the $GRIND VIBECODE HACKATHON on Abstract Chain. The game combines classic tower defense mechanics with innovative blockchain features through the integration of the $GRIND token.

⚠️ **WARNING: This project is in test phase for the $GRIND VIBECODE HACKATHON. DO NOT use mainnet wallets with this application. Only use testnet wallets specifically created for testing purposes.**

## Main Features

- **Tower Defense Gameplay**: Place towers, defend your coffee shop against waves of enemies
- **$GRIND Token Integration**: Use the $GRIND token for various features in the game
- **Token Sinks**: Multiple mechanisms to create constant demand for the $GRIND token
- **Grind Mascot**: Complete integration of the Grind mascot (orange hamster with pink hat)
- **Responsive Interface**: Playable on computers and mobile devices
- **Day/Night Mode**: For better readability on all devices
- **Internationalization**: Available in French and English
- **Web3 Authentication**: Via Privy and Abstract Global Wallet

## $GRIND Token

The $GRIND token is the main utility token of the game with several utilities:

1. **Purchase of Power-ups and Upgrades**: Spend tokens to get advantages in the game
2. **Burning System for Unique Rewards**: Burn tokens for permanent rewards
3. **Staking with Time Lock**: Stake your tokens for passive rewards
4. **Real Coffee Orders**: Use your tokens to order coffee from makingcoffee.com

**Note**: The $GRIND token is developed and deployed by the Grind The Coin team on Abstract testnet. This project integrates with the existing token and does not create its own version of $GRIND.

## Grind Mascot

The Grind mascot is integrated into the game in six different ways:

1. **Guide/Narrator Character**: Grind guides you through the game
2. **Special "Grind Hamster" Tower**: A unique tower with special abilities
3. **Shop Mascot**: Grind manages the in-game shop
4. **"Supreme Karen" Boss**: A special boss who has captured Grind
5. **Companion System**: Grind follows you and helps you during the game
6. **"Grind Runner" Mini-game**: A mini-game where you control Grind

## Installation and Launch

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/coffee-defense.git
cd coffee-defense

# Install website dependencies
cd coffee-defense-website
npm install

# Launch the development server
npm run dev
```

### Deployment

```bash
# Build the site for production
npm run build

# Start the production server
npm start
```

## Project Structure

```
/CoffeeDefense/
  /Assets/
    /Scripts/
      GrindTokenInterface.js  # Interface to interact with $GRIND token
      GrindTokenSinks.js      # Implementation of token sinks
      MakingCoffeeIntegration.js  # Integration with makingcoffee.com
      GrindMascotIntegration.js   # Integration of the Grind mascot
  
/coffee-defense-website/
  /src/
    /app/
      /auth/          # Authentication system
      /game/          # Coffee Defense game
      /grind/         # Page dedicated to the $GRIND token
      /whitepaper/    # Project whitepaper
```

## Technologies Used

- **Frontend**: Next.js, React, TailwindCSS
- **Blockchain**: Abstract Chain, Solidity
- **Authentication**: Privy, Abstract Global Wallet
- **Internationalization**: i18n
- **Deployment**: Vercel

## Documentation

Complete documentation is available in the `/coffee-defense-website/public/documentation.md` folder.

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is under the MIT license. See the LICENSE file for more details.

## Credits

- **Development**: Manus
- **Founder**: Rana Stoica
- **Contact**: contact@ranastoica.xyz
- **Social Media**: 
  - Lens: [@ranastoica](https://lenster.xyz/u/ranastoica)
  - Farcaster: [@ranastoica](https://warpcast.com/ranastoica)
  - X: [@LaGrenouilleETH](https://twitter.com/LaGrenouilleETH)
