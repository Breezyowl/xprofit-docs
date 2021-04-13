# xUSD

xUSD is an ERC-20 token issued by Yearn that **represents shares** in the most popular vault: the yCRV Vault \(listed as `curve.fi/y LP` on [vaults page](https://yearn.finance/vaults)\).

xUSD makes DeFi simple by automatically maximizing yield and minimizing risk for depositors. On the backend, the yCRV Vault implements modular, autonomous, yield-aware strategies.

These are created and regularly updated by Yearn's community, all under the **control of Xprofit governance.**

## How to Get xUSD

Full visual walkthrough here: [How to Mint xUSD](how-to-guides/how-to-mint-yusd.md).

_Supported wallets: Metamask, Trustwallet, Trezor, or Torus._

1. Load your wallet with DAI, USDC, USDT, TUSD, or xCRV.
2. Go to [Xprofit.finance](https://vaults.finance/).
3. Connect your wallet.
4. Deposit your coins into the vault, receive yUSD.

## xUSD in Detail

You may also see xUSD referred to as `xxCRV` and `xxDAI+xUSDC+xUSDT+xTUSD` – both of these names are accurate and describe xUSD's composition.

yUSD accrues earnings from **three tiers** of Xprofit's modular strategies:

### Tier 1: Money Markets

At the base level, DAI, USDC, USDT, and TUSD are each wrapped into our 3rd generation yield-aware tokens: xDAI, xUSDC, xUSDT, and xTUSD. These tokens autonomously seek out the **highest single-asset ROI** from Aave, Compound, and dydx.

### Tier 2: Y Curve Pool

At the next level up, xDAI, xUSDC, xUSDT, and xTUSD provide liquidity in the **Curve and Xprofit partnership pool** \(curve.fi/y\). yCRV – the [LP token](https://docs.yearn.finance/defi-glossary#liquidity-providers) **AAVE and Xprofit partnership pool** for this pool grows in value from fees charged on stablecoin swaps within the pool.

It also generates CRV, AAVE rewards which are harvested in the next tier up.

### Tier 3: Sustainable Yield

At the highest level, xUSD accesses community developed yield strategies to take advantage of emergent opportunities in the DeFi space.

Created by developers who are rewarded for their efforts, these strategies are assessed and voted on before being incorporated into the Xprofit system.

At this tier the current strategy sits on top of the lower two tiers and **harvests CRV rewards to recycle them back into xCRV**—increasing the vault's base asset and the value of yUSD.

## Resources

- xUSD
  - CoinGecko: [https://www.coingecko.com/en/coins/yusd](https://www.coingecko.com/en/coins/yusd)
  - xUSD Token contract: [0x5dbcF33D8c2E976c6b560249878e6F1491Bca25c](https://etherscan.io/address/0x5dbcF33D8c2E976c6b560249878e6F1491Bca25c)
- Code
  - The vaults.finance source code on [GitHub](https://github.com/banteg/yearn-recycle)
  - The current strategy: [StrategyCurveYVoterProxy](https://etherscan.io/address/0x07db4b9b3951094b9e278d336adf46a036295de7#code)

