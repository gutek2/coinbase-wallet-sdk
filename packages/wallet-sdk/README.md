# Coinbase Wallet SDK

Coinbase Wallet SDK lets developers connect their dapps to Coinbase Wallet
on both mobile web (for iOS and Android) and desktop:

- **Mobile**: Users can connect to your mobile web dapp through a deeplink to the dapp browser in [Coinbase Wallet Mobile App](https://coinbase-wallet.onelink.me/q5Sx/fdb9b250).

- **Desktop**: Users can connect to your desktop app with a QR code in the [Coinbase Wallet Mobile App](https://coinbase-wallet.onelink.me/q5Sx/fdb9b250) or with the [Coinbase Wallet Chrome Extension](https://coinbase-wallet.onelink.me/q5Sx/fdb9b250).

## Installing and Upgrading

> The installation package for **Coinbase Wallet SDK** (formerly WalletLink) is now named `@coinbase/wallet-sdk`.

- This readme contains brief instructions to get up and running.
- Visit our [public developer docs](https://docs.cloud.coinbase.com/wallet-sdk/docs) for more detail, including samples for integrating Coinbase Wallet using libraries like [web3-react](https://github.com/Uniswap/web3-react), [web3modal](https://github.com/Web3Modal/web3modal), [Web3-Onboard](https://docs.blocknative.com/onboard), and [wagmi](https://wagmi.sh/).

### Installing Wallet SDK

Install Coinbase Wallet SDK with yarn or npm.

#### Yarn

1. Check available versions of Wallet SDK.

```shell
yarn info @coinbase/wallet-sdk versions
```

2. Install a specific version or the latest version.

```shell
#yarn add @coinbase/wallet-sdk@3.0.0
yarn add @coinbase/wallet-sdk
```

3. Check your installed version.

```shell
yarn list @coinbase/wallet-sdk
```

#### Npm

1. Check available versions of Wallet SDK.

```shell
npm view @coinbase/wallet-sdk versions
```

2. Install a specific version or the latest version.

```shell
#npm install @coinbase/wallet-sdk@3.0.0
npm install @coinbase/wallet-sdk
```

3. Check your installed version.

```shell
npm list @coinbase/wallet-sdk
```

### Upgrading Wallet SDK

Upgrade Coinbase Wallet SDK with yarn or npm.

#### Yarn

1. Compare your installed version of Coinbase Wallet SDK with the latest available version.

```shell
yarn outdated @coinbase/wallet-sdk
```

2. Update Coinbase Wallet SDK to the latest.

```shell
yarn upgrade @coinbase/wallet-sdk --latest
```

#### Npm

1. Compare your installed version of Coinbase Wallet SDK with the latest available version.

```shell
npm outdated @coinbase/wallet-sdk
```

2. If necessary, update `package.json` with the latest major version.

```shell
{
  "dependencies": {
    "@coinbase/wallet-sdk": "^3.0.0"
  }
}
```

3. Update Coinbase Wallet SDK to the latest available version.

```shell
npm update @coinbase/wallet-sdk
```

## Attributions

- [eth-rpc-errors](https://github.com/MetaMask/eth-rpc-errors/blob/main/LICENSE) under the MIT license
