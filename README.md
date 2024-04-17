# dEquity tokens

## Description

### Mechanics

DEQTY utility tokens of dEquity.io – Real-World Assets tokenization platform

We launch dequity.io/token page with information regarding token sale launch on 17 april 2024.

User starts with wrapping stablecoins USDT into wUSD – working capital tokens*.

User adds liquidity to DEQTY/wUSD pair on web3.world , receiving LP tokens.
User dynamic stake LP tokens in one of 2 staking options which determine the exit term:
- 9 month exit term option
- 18 month exit term option

* `*` Working capital is used directly for purchasing real-estate properties. So we get only locked stakes for 9 or 18 months minimum.
* `**` We have Working Capital Vault NFT pool where each NFT is minted against 100 wUSD. NFT pool is governed by DAO. Each Working Capital Vault NFT can be swapped 1:1 for future Property NFT.

## Features

- Wrapper USDT/wUSD 1:1 
- Staker for LP tokens with 9 month exit term
- Staker for LP tokens with 18 month exit term

## Installation

1. Clone the repository.
2. Install the dependencies.
3. Run the project.

## Testing

1. Start local venom node.
```
docker run -d -e USER_AGREEMENT=yes --rm --name local-node -p80:80 tonlabs/local-node
```
2. Start tests.
```
npx locklift test -n local
```


## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- Email: info@dequity.io
- Twitter: [@_dEquity](https://twitter.com/_dEquity)
