# Verus Community App Store for umbrelOS

A community app store for [umbrelOS](https://umbrel.com) with two apps:

- **Verus Node** (`dwarner-verus`) – a Verus (VRSC) full node running the official `verusd`, with a dashboard for sync progress, peers and connection details. The image is built from [dwarner5522/umbrel-verus](https://github.com/dwarner5522/umbrel-verus).

- **Verus Electrum Server** (`dwarner-verus-electrum`) – an Electrum server for Verus lite wallets, indexing the blockchain from Verus Node. It requires Verus Node. The image is built from [dwarner5522/umbrel-verus-electrum](https://github.com/dwarner5522/umbrel-verus-electrum).

## Add it to your Umbrel

1. Open the App Store on your Umbrel.
2. Click the `…` menu in the top right and choose **Community App Stores**.
3. Paste `https://github.com/dwarner5522/umbrel-verus-app-store` and click **Add**.
4. Open the **Verus Community App Store** and install **Verus Node**. Once it has synced, install **Verus Electrum Server** if you want one.

This is a community package and is not maintained by the Verus Coin Foundation or Umbrel.
