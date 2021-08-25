# Debugging

> The process of identifying and removing errors from computer hardware or software.

## Local mainnet forking

In order to test integrations between web and blockchain locally, you can fork mainnets locally:

```
npm i -g ganache-cli
ganache-cli --fork https://mainnet.infura.io/v3/<YOUR_API_KEY>
```

You will find our infura api key in 1Password.
