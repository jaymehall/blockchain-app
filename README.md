# ERC20 Token - Fortune Token (FTN)

## Description

This application builds and deploys an ERC20 token in compliance with EIP standards, along with an exchange for trading it. It uses two Solidity smart contracts — one for the token, one for the exchange — with a React front end using Redux for global state management.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)
- [Tests](#tests)
- [Next Steps](#next-steps)
- [Questions](#questions)

## Installation

```
npm install
```

Compile and migrate the smart contracts to a local blockchain (e.g. Ganache):

```
truffle compile
truffle migrate
```

## Usage

Start the React app:

```
npm start
```

Connect a Web3 wallet (e.g. MetaMask) to interact with the deployed Token and Exchange contracts.

## Technologies

- React.js
- JavaScript
- Node.js
- Solidity
- Truffle (Mocha and Chai testing frameworks built in)
- NPM

## License

[MIT](https://opensource.org/licenses/MIT)

![License: MIT](https://img.shields.io/badge/License-MIT-9cf)

## Tests

Tests are created for each smart contract in the application:

```
truffle test
```

- `Token.test.js`
- `Exchange.test.js`

## Next Steps

No further work planned at this time.

## Questions

For additional questions please contact:

- Jayme Hall
- GitHub: [https://github.com/jaymehall/](https://github.com/jaymehall/)
- LinkedIn: [https://www.linkedin.com/in/jayme-hall/](https://www.linkedin.com/in/jayme-hall/)
