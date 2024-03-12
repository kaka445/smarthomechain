# SmartHomeChain

**SmartHomeChain** offers an innovative approach to smart home management by integrating blockchain technology for device authentication and action verification, utilizing **Web3Things** for blockchain interactions and **DeviceVerifier** for secure device communications.

## Features

- Secure device commands with JWT authentication.
- Leverage blockchain for device action verification and data integrity.
- Integrated solution using Web3Things and DeviceVerifier.

## Installation

```bash
npm install smarthomechain
```

## Usage

Ensure Web3Things and DeviceVerifier are set up:

```bash
const SmartHomeChain = require('smarthomechain');
const smartHome = new SmartHomeChain('https://mainnet.infura.io/v3/YOUR_PROJECT_ID', 'mqtt://broker.hivemq.com', 'yourSecret');

smartHome.secureDeviceCommunication('deviceId123', 'turnOn');


```
SmartHomeChain transforms your home into a secure, blockchain-integrated ecosystem, where every device action is authenticated and recorded. SmartHomeChain simplifies smart home automation with enhanced security and blockchain integration.