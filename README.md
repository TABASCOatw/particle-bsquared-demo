<div align="center">
  <a href="https://particle.network/">
    <img src="https://i.imgur.com/P391e8h.png" />
  </a>
  <h3>
    Particle Network BTC Connect B² Demo
  </h3>
</div>

⚡️ Demo application showcasing the implementation of Particle Network's BTC Connect product to facilitate ERC-4337 Account Abstraction (through native Bitcoin wallets) on B², a ZK-Rollup for Bitcoin boasting quick transaction speeds, low fees, and of course, data settlement on Bitcoin.

Built using **BTC Connect (by Particle Network)**, **TypeScript**

## ₿ BTC Connect
BTC Connect takes advantage of ERC-4337 alongside (Bitcoin) Layer-2 EVM-compatible blockchains to leverage a Smart Account, Paymaster, Bundler natively within Bitcoin wallets (connected to through a Bitcoin-specific modal also provided by BTC Connect). As its core, BTC Connect enables existing BTC wallets to control smart accounts on Layer-2s.

![](https://i.imgur.com/xOOsvtK.png)

##

<p align="center">
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/TABASCOatw/particle-bsquared-demo&env=REACT_APP_PROJECT_ID&env=REACT_APP_CLIENT_KEY&env=REACT_APP_APP_ID&envDescription=Head%20over%20to%20the%20Particle%20dashboard%20to%20retrieve%20the%20above%20keys.&envLink=https%3A%2F%2Fdashboard.particle.network">
    <img src="https://vercel.com/button" alt="Deploy with Vercel"/>
  </a>
</p>


##

👉 Try the demo: https://btc-connect-demo.particle.network (or the alternative learning-oriented demo similar to the application covered within this repository, https://particle-btc-connect-demo.replit.app)

👉 Learn more about Particle Network: https://particle.network

## 🛠️ Quickstart

### Clone this repository
```
git clone https://github.com/TABASCOatw/particle-bsquared-demo.git
```

### Install dependencies
```
yarn install
```
OR
```
npm install
```

### Set environment variables
This project requires a number of keys from Particle Network to be defined in `.env`. The following should be defined:
- `REACT_APP_APP_ID`, the ID of the corresponding application in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).
- `REACT_APP_PROJECT_ID`, the ID of the corresponding project in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).
-  `REACT_APP_CLIENT_KEY`, the client key of the corresponding project in your [Particle Network dashboard](https://dashboard.particle.network/#/applications).

### Start the project
```
npm run dev
```
OR
```
yarn dev
```
