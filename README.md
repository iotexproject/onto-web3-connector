# Install

```
$ npm i @iotexproject/onto-connector
$ yarn add @iotexproject/onto-connector
```

# Usage

```javascript
// https://github.com/NoahZinsmeister/web3-react
const ontoConnector = new OnToConnector({ supportedChainIds: [1, 3] });

const { activate, deactivate, library, account, error } = useWeb3React();

activate(ontoConnector);
```
