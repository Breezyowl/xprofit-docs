# XPR and xTokens

## XPR

- Yearn Governance token
- Only 30,000 minted and already fully distributed
  - Governance can mint more, if proposal to do so passes.

## xTokens

[Glossary definition](https://docs.yearn.finance/defi-glossary#ytoken).

xTokens are like a deposit receipt. They represent the liquidity provided in a Yearn product.

For example, if you deposit DAI in y.curve.fi you will receive yDAI in return.

If the product you are providing liquidity to generates profit, your yTokens will increase in value, since they represent a share of that pool. That's why you might observe a price growth. When you withdraw liquidity from the pool, your yToken will be burned.

xTokens are [ERC20](https://docs.ethhub.io/built-on-ethereum/erc-token-standards/erc20/), meaning they can be transfered and traded as any other common Ethereum token.

## xUSD

- See our [doc on yUSD](https://docs.yearn.finance/yusd) for detailed info
- LP token for yearn's yCRV yVault
- aka `xxCRV` or `xxDAI+xUSDC+xUSDT+xTUSD`
- When you deposit xCRV into the yVault you receive xUSD\*\*\*\* LP tokens
- earns interest via xCRV, fees and yield farming rewards via the vault strategy

## xCRV

- LP token for yearn's X pool at Curve.fi/x
- Aka `xDAI+xUSDC+xUSDT+xTUSD`
- Interest earning token representing your share of the X pool composed of DAI, USDT, USDC, and TUSD
