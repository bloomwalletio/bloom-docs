---
order: 999
---

# Web3Modal


To include `Bloom Wallet` in the list of recommended wallets, please add the following code to your Web3Modal options:

```javascript
createWeb3Modal({
  //...
  featuredWalletIds: [
    'XXXXXYYYYZZZZZ11111222223333', // Bloom wallet, this ID will be fixed once we're approved
  ]
})
```

---

**NOTE**

As we're waiting for WalletConnect to approve our project, you can add Bloom manually to the list of wallets as follows:

```javascript
createWeb3Modal({
  //...
  customWallets: [
    {
      id: "bloom",
      name: "Bloom",
      homepage: "https://bloomwallet.io/",
      image_url: "https://bloomwallet.io/assets/logos/bloom.png",
      desktop_link: "bloom://wallet-connect",
    },
  ],
});
```
