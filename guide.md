## Running L2 Node on local connected to Kovan L1

```
yarn prod:initialize 0xC34Fd04E698dB75f8381BFA7298e8Ae379bFDA71 https://kovan.infura.io/v3/04b85e5c71a042c09a1c3684586e3288 --password pass
yarn deploy:validators 0xC34Fd04E698dB75f8381BFA7298e8Ae379bFDA71 --password pass
```

You will see two different addresses.

You need to send those addresses Some ETHs on Kovan testnet. After addresses get ETHs node will start syncing.