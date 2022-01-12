# useWeb3

[![NPM](https://img.shields.io/npm/v/@w3u/useweb3.svg)](https://www.npmjs.com/package/useWeb3) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
# Use yarn
yarn add @w3u/useweb3

# Use npm
npm install --save @w3u/useweb3
```

## Usage

```tsx
import React  from 'react'
import { Web3Provider } from '@w3u/useWeb3'

ReactDOM.render(
  <React.StrictMode>
    <Web3Provider
      config={{
        supportedChainIDs: [1, 56]
      }}
    >
      <App />
    </Web3Provider>
  </React.StrictMode>,
  document.getElementById('root')
)

```

## License

MIT © [w3u](https://github.com/thew3u/useWeb3)
