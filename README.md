# 🛠️ debug-eth-contract

### This is a  react component to debug a solidity contract  . Made with typescript ,wagmi,etherjs and scaffold-eth

[DEMO](http://debug-eth-contract-demo.surge.sh)

## usage
### import DebugContract
```js
import { DebugContract } from "debug-eth-contract";
```
#### props to pass
1. DebugContract component accepts the contracts props as array. 
2.  inside  contracts array pass {contrractName,contract} object
3.  here conract property is your contract instance with its provider
```js
<DebugContract contracts={[
               { contractName: "YourContract", contract: contract },
               { contractName: "YourContract", contract: contract },
            ]} />
```

###### for working example code  check example folder in this repo




## Guides


- Check out [wagmi hooks  docs](https://wagmi.sh/docs/getting-started) for example of how to use hooks
- you can look at [speedrun ethereum](https://speedrunethereum.com/) to get started with scaffold-eth-typescript and web3.  
  - 🏁 Make sure to click on the typescript tab!

## 🏃💨 Speedrun Ethereum
Register as a builder [here](https://speedrunethereum.com) and start on some of the challenges and build a portfolio.
# More Information!

## 📚 Documentation

Documentation, tutorials, challenges, and many more resources, visit: [docs.scaffoldeth.io](https://docs.scaffoldeth.io)

Eth-hooks documentation is [here](https://scaffold-eth.github.io/eth-hooks/).  Learn how to use the contexts here.


### 🔭 Learning Solidity

Read the docs: https://docs.soliditylang.org

Go through each topic from [solidity by example](https://solidity-by-example.org) editing `YourContract.sol` in **🏗 scaffold-eth**


## 🛠 Buidl

Check out all the [active branches](https://github.com/austintgriffith/scaffold-eth/branches/active), [open issues](https://github.com/austintgriffith/scaffold-eth/issues), and join/fund the 🏰 [BuidlGuidl](https://BuidlGuidl.com)!

[Follow the full Ethereum Speed Run](https://medium.com/@austin_48503/%EF%B8%8Fethereum-dev-speed-run-bd72bcba6a4c)

### 💬 Support Chat

Join the telegram [support chat 💬](https://t.me/joinchat/KByvmRe5wkR-8F_zz6AjpA) to ask questions and find others building with 🏗 scaffold-eth!

### 🙏🏽 Support us!

Please check out our [Gitcoin grant](https://gitcoin.co/grants/2851/scaffold-eth) too!


## 🔐 P.S.About keys

You need an RPC and API keys for testnets and production deployments, create an [Alchemy](https://www.alchemy.com/) account and replace the value of `ALCHEMY_KEY = xxx` in `packages/vite-app-ts/.env` with your new keys.



