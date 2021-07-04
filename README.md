# Deployments

## Rewards

The two main mining mechanism are `Swap Mining` and `LP Mining`

### Swap Mining

`Swap Mining` allows users that use swap to balance the hourglass pool to receive `HOUR` rewards proportionally to their swap volume.

### LP Mining

LP mining allows users stake their LP tokens (e.g `HOUR/USDC`, `hourUSD`) to earn more `HOUR`.

### Vault

`HOUR` holder can enter `Vault` to earn governance right to the Hourglass protocol. All mined `HOUR` rewards enter the vault first by default upon claim. Users can choice to exit anytime they wish. 

Upon exiting vault, a 10% exit fee is taken and distributed as following:
- 2% of withdraw amount is burnt.
- 4% is sent to DAO and becomes apart of `protocol controlled value (PCV)`.
- 4% is distributed to the rest of the vault pool.

## DAO

The DAO `Treasury` receives token from `swapping fees` and `Vault`, and performs buyback and add to LP.

For example, the treasury receives `USDC` from the hourglass pool as swapping fee. It then sells half of the `USDC` for `HOUR`, and add to `USDC/HOUR LP`.

![Alt text](TODO: diagram)

## Contract Addresses
[address.js](address.js)
