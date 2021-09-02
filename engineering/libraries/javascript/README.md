
## Dependency trees of DePay's JavaScript libraries

### Without any dependencies

[depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)

[depay-local-currency](https://github.com/DePayFi/depay-local-currency)

[depay-react-dialog](https://github.com/DePayFi/depay-react-dialog)

[depay-react-shadow-dom](https://github.com/DePayFi/depay-react-shadow-dom)

### With one level dependencies

```
[depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│
└── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-mock](https://github.com/DePayFi/depay-web3-mock)
│
└── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-react-dialog-stack](https://github.com/DePayFi/depay-react-dialog-stack)
│
└──[depay-react-dialog](https://github.com/DePayFi/depay-react-dialog)

[depay-react-token-image](https://github.com/DePayFi/depay-react-token-image)
│
├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
```

### With multi-level dependencies

```
[depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
└── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │
    └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│
└── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │
    └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-assets](https://github.com/DePayFi/depay-web3-assets)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │
│   └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-client](https://github.com/DePayFi/depay-web3-wallets)
    │
    └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
        │
        └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │
    └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)


[depay-web3-exchanges](https://github.com/DePayFi/depay-web3-exchanges)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
    │
    ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │
    ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
    │   │
    │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
        │
        └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

[depay-web3-payments](https://github.com/DePayFi/depay-web3-payments)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-web3-assets](https://github.com/DePayFi/depay-web3-assets)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   ├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   ├── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │   │
│   │   └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-client](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│           │
│           └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│   │   │
│   │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │       │
│   │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-exchanges](https://github.com/DePayFi/depay-web3-exchanges)
    │
    ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │
    ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
    │   │
    │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    ├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
    │   │
    │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │   │
    │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    └── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
        │
        ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
        │
        ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
        │   │
        │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
        │       │
        │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
        │
        └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
            │
            └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
 ```

### Bundled libraries

```
[depay-widgets] https://github.com/DePayFi/depay-widgets
│
├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-local-currency](https://github.com/DePayFi/depay-local-currency)
│
├── [depay-react-shadow-dom](https://github.com/DePayFi/depay-react-shadow-dom)
│
├── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │
│   └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-react-dialog-stack](https://github.com/DePayFi/depay-react-dialog-stack)
│   │
│   └──[depay-react-dialog](https://github.com/DePayFi/depay-react-dialog)
│
├── [depay-react-token-image](https://github.com/DePayFi/depay-react-token-image)
│   │
│   ├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│
├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│       │
│       └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│           │
│           └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-assets](https://github.com/DePayFi/depay-web3-assets)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   ├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   ├── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │   │
│   │   └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-client](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│           │
│           └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│   │   │
│   │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │       │
│   │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │
│       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
├── [depay-web3-exchanges](https://github.com/DePayFi/depay-web3-exchanges)
│   │
│   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │
│   ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│   │   │
│   │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │       │
│   │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   ├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
│   │   │
│   │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│   │   │
│   │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│   │       │
│   │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│   │
│   └── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
│       │
│       ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
│       │
│       ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
│       │   │
│       │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│       │       │
│       │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│       │
│       └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
│           │
│           └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
│
└── [depay-web3-payments](https://github.com/DePayFi/depay-web3-payments)
    │
    ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │
    ├── [depay-web3-assets](https://github.com/DePayFi/depay-web3-assets)
    │   │
    │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │   │
    │   ├── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │   │
    │   ├── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │   │   │
    │   │   └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │   │
    │   └── [depay-web3-client](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │           │
    │           └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    ├── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
    │   │
    │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │   │
    │   ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
    │   │   │
    │   │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │   │       │
    │   │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │   │
    │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    ├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
    │   │
    │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
    │   │
    │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
    │       │
    │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
    │
    └── [depay-web3-exchanges](https://github.com/DePayFi/depay-web3-exchanges)
        │
        ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
        │
        ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
        │   │
        │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
        │       │
        │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
        │
        ├── [depay-web3-transaction](https://github.com/DePayFi/depay-web3-transaction)
        │   │
        │   ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
        │   │
        │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
        │       │
        │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
        │
        └── [depay-web3-tokens](https://github.com/DePayFi/depay-web3-tokens)
            │
            ├── [depay-web3-constants](https://github.com/DePayFi/depay-web3-constants)
            │
            ├── [depay-web3-client](https://github.com/DePayFi/depay-web3-client)
            │   │
            │   └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
            │       │
            │       └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)
            │
            └── [depay-web3-wallets](https://github.com/DePayFi/depay-web3-wallets)
                │
                └── [depay-web3-blockchains](https://github.com/DePayFi/depay-web3-blockchains)

```
