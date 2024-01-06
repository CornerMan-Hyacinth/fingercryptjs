# FingerCrypt JS

A JavaScript library for secure fingerprint authentication with blockchain integration.

### NOTE

Until otherwise stated by the author, this library is still under development and has not be tested thoroughly. Hence, it shouldn't be used for any project under production.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Installation

```bash
npm install your-library-name
```

## Usage

```javascript
// Import the library
const yourLibrary = require("your-library-name");

// Use the library
yourLibrary.collectFingerprint(/* ... */);
yourLibrary.encryptFingerprint(/* ... */);
yourLibrary.storeInBlockchain(/* ... */);
```

## Configuration

Configure the library with your blockchain endpoint, contract address, and other parameters.

```javascript
const yourLibrary = require("fingercryptjs");

// Set configuration
yourLibrary.configure({
  blockchainEndpoint: "https://your-blockchain-endpoint.com",
  contractAddress: "0xYourContractAddress",
  // Other configuration options
});
```

## Examples

Explore the example/ directory for a sample React Native app demonstrating library usage.

## Documentation

For detailed documentation, please refer to Documentation.md.

## Contributing

1. Fork the repository
2. Create a new branch (git checkout -b feature/new-feature)
3. Make your changes and commit (git commit -am 'Add new feature')
4. Push to the branch (git push origin feature/new-feature)
5. Create a pull request
6. License
7. This project is licensed under the MIT License - see the LICENSE file for details.
