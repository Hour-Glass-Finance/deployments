# Deployments

## Rewards

The two main mining mechanism are Volume Mining and LP Mining

### Volume Mining

Volume Mining allows users that swap stable coins in the hourglass pool to receive HOUR rewards proportionally to their swap volume.

### LP Mining

LP mining allows users stake their LP tokens (e.g HOUR/USDC, hourUSD) to earn more HOUR.
TODO: mint hourUSD

### Vault

All mined rewards enter the Vault. Users can choice to exit anytime they wish. Upon exit the following occurs:
- 2% of withdraw amount is burnt.
- 4% is sent to DAO.
- 4% is distributed to the rest of the Vault staking pool.

## DAO

The DAO treasury contract receives token from the hourglass pool and vault, and performs buyback and add to LP.

For example, the treasury receives USDC from the hourglass pool. It then sells half of the USDC for HOUR, and add to LP.

![Alt text](TODO: diagram)

## Contract Addresses
[address.js](address.js)
