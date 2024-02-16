# Aptogotchi Random Mint

We have a tutorial based on this repo at [Aptos Learn](https://learn.aptoslabs.com/), go check it out!

## Difference from [Aptogotchi beginner](https://github.com/aptos-labs/aptogotchi)

This is a simplified version that only keeps minting function, it uses On-Chain randomness to determine the look of Aptogotchi at minting instead of manually setting it, and each address can mint as many Aptogotchis as possible instead of 1 per address.

## Prerequisite

The module is deployed to [randomnet](https://explorer.aptoslabs.com/?network=randomnet), which is a standalone network different from mainnet and testnet. It has its own chain ID and you need to get randomnet APT.

To add randomnet to your petra wallet, click add network in setting.
Name enters `randomnet`.
Node url enters `https://fullnode.random.aptoslabs.com/v1`.
Faucet url enters `https://faucet.random.aptoslabs.com`.
