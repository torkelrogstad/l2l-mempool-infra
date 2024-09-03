This repository contains a Docker Compose configuration file for deploying the
following components:

1. A BIP300/BIP301 (Drivechain) enabled Bitcoin Core node:
   https://github.com/layerTwo-Labs/mainchain/

2. An Electrum server: https://github.com/torkelrogstad/electrs

3. An instance of mempool.space: https://github.com/torkelrogstad/mempool

The last two components here are forks of the upstream Mempool projects. They
have been lightly modified to be Drivechain compatible.

The Mempool instance is available at https://mempool.drivechain.live. The
Electrum server is available at `tcp://drivechain.live:50001`.
