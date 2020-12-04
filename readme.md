# FlexAssets contract code for Ethereum

These contracts work together to create an upgradeable contract representing an underlying asset such as USDC, BTC or ETH that can be paid interest through a rebase. User balances go up automatically as the underlying assets [earn interest](https://coinflex.com/blog/coinflex-launches-interest-bearing-stablecoin/) on the Coinflex exchange.

All flexAssets can be minted or redeemed on the [Coinflex flexAssets](https://coinflex.com/flexassets) portal. The assets are put at work in the Coinflex repo orderbook enabling a tight connection between Coinflex's [deliverable perpetual contracts](https://coinflex.com/support/deliverable-perpetual-futures/) and the spot market. An [FAQ is available](https://coinflex.com/support/2-2-7-flexassets/).

flexAssets can be withdrawn from the exchange at any time and used as a means of payment or for trading purposes, all while earning interest automatically through the exchange.

## Smart contract notes

Coinflex pays interest by rebasing balances for all addresses. The contract enforces the condition that balances can only go up. 

At present flexUSD, flexBTC and flexETH have been deployed. They are available on Etherscan at the following addresses:

1. flexUSD [0xa774FFB4AF6B0A91331C084E1aebAE6Ad535e6F3](https://etherscan.io/address/0xa774FFB4AF6B0A91331C084E1aebAE6Ad535e6F3)
2. flexBTC [0x2B93824ad1c8c2DD79351FaCaE9473eAEf062366](https://etherscan.io/address/0x2B93824ad1c8c2DD79351FaCaE9473eAEf062366)
3. flexETH [0x40fB4096E0ACbf97D0087C3b7e4c6794Aa24a32f](https://etherscan.io/address/0x40fB4096E0ACbf97D0087C3b7e4c6794Aa24a32f)

More deployments will occur shortly.
