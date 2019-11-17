# `web3-react` 🧰

_A simple, maximally extensible, dependency minimized framework for building modern Ethereum dApps_

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[![Actions Status](https://github.com/NoahZinsmeister/web3-react/workflows/CI/badge.svg)](https://github.com/NoahZinsmeister/web3-react/actions)

| Packages                              | `@latest` Version                                                                                                                                                         | Size                                                                                                                                                                                 | Description                                                                         |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| 🏠 **Core**                           |
| `@web3-react/core`                    | [![npm version](https://img.shields.io/npm/v/@web3-react/core/latest.svg)](https://www.npmjs.com/package/@web3-react/core/v/latest)                                       | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/core/latest.svg)](https://bundlephobia.com/result?p=@web3-react/core@latest)                                       | [React](https://reactjs.org/) Interface                                             |
| 🔌 **Connectors**                     |
| _Browser Extension/dApp Browser_      |
| `@web3-react/injected-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/injected-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/injected-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/injected-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/injected-connector@latest)           | [Injected](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1193.md) Connector |
| _Remote API_                          |
| `@web3-react/network-connector`       | [![npm version](https://img.shields.io/npm/v/@web3-react/network-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/network-connector/v/latest)             | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/network-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/network-connector@latest)             | Network (RPC) Connector                                                             |
| _QR Code_                             |
| `@web3-react/walletconnect-connector` | [![npm version](https://img.shields.io/npm/v/@web3-react/walletconnect-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/walletconnect-connector/v/latest) | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/walletconnect-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/walletconnect-connector@latest) | [WalletConnect](https://walletconnect.org/) Connector                               |
| `@web3-react/walletlink-connector`    | [![npm version](https://img.shields.io/npm/v/@web3-react/walletlink-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/walletlink-connector/v/latest)       | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/walletlink-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/walletlink-connector@latest)       | [WalletLink](https://www.walletlink.org/#/) Connector                               |
| _Native_                              |
| `@web3-react/frame-connector`         | [![npm version](https://img.shields.io/npm/v/@web3-react/frame-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/frame-connector/v/latest)                 | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/frame-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/frame-connector@latest)                 | [Frame](https://frame.sh/) Connector                                                |
| _Hosted_                              |
| `@web3-react/fortmatic-connector`     | [![npm version](https://img.shields.io/npm/v/@web3-react/fortmatic-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/fortmatic-connector/v/latest)         | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/fortmatic-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/fortmatic-connector@latest)         | [Fortmatic](https://fortmatic.com/) Connector                                       |
| `@web3-react/portis-connector`        | [![npm version](https://img.shields.io/npm/v/@web3-react/portis-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/portis-connector/v/latest)               | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/portis-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/portis-connector@latest)               | [Portis](https://www.portis.io/) Connector                                          |
| `@web3-react/squarelink-connector`    | [![npm version](https://img.shields.io/npm/v/@web3-react/squarelink-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/squarelink-connector/v/latest)       | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/squarelink-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/squarelink-connector@latest)       | [Squaerlink](https://squarelink.com/) Connector                                     |
| `@web3-react/torus-connector`         | [![npm version](https://img.shields.io/npm/v/@web3-react/torus-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/torus-connector/v/latest)                 | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/torus-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/torus-connector@latest)                 | [Torus](https://tor.us/) Connector                                                  |
| `@web3-react/authereum-connector`     | [![npm version](https://img.shields.io/npm/v/@web3-react/authereum-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/authereum-connector/v/latest)         | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/authereum-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/authereum-connector@latest)         | [Authereum](https://authereum.org/) Connector                                       |
| 🐉 **Low-Level**                      |
| `@web3-react/abstract-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/abstract-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/abstract-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/abstract-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/abstract-connector@latest)           | Shared Connector Class                                                              |
| `@web3-react/types`                   | [![npm version](https://img.shields.io/npm/v/@web3-react/types/latest.svg)](https://www.npmjs.com/package/@web3-react/types/v/latest)                                     | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/types/latest.svg)](https://bundlephobia.com/result?p=@web3-react/types@latest)                                     | Shared [TypeScript](https://www.typescriptlang.org/) Types                          |

## Quickstart

[![Edit web3-react-v6](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/web3-react-v6-8rg3h?fontsize=14&hidenavigation=1&theme=dark)

## Documentation

Coming soon™️ 😁

## Local Development

- Clone repo\
  `git clone https://github.com/NoahZinsmeister/web3-react.git`

- Install top-level dependencies\
  `yarn`

- Install sub-dependencies\
  `yarn bootstrap`

- Build\
  `yarn build`

- Watch for changes\
  `yarn start`
