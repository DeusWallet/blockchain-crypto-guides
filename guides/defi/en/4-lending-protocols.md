# Lending Pools

Lending pools are DeFi services that facilitate non-custodial cryptocurrency lending and borrowing.

## Borrowing

Borrowing services allow users to borrow cryptocurrency from a smart contract by providing collateral in another cryptocurrency. This lets borrowers access liquidity without selling their cryptocurrency. Borrowers can repay the loan anytime to retrieve their collateral.

## Lending

Lending services enable cryptocurrency holders to lend assets to a smart contract and earn interest. Lenders can withdraw their deposits along with accrued interest at any time.

Typically, market participants borrow assets from a smart contract to utilize these funds in activities that yield higher returns than the borrowing cost. For example, someone might borrow one cryptocurrency from one DeFi service and lend it to another service offering higher returns.

## Collateralized Loans

- Borrowers must put up another cryptocurrency as collateral, often significantly more than the borrowed amount.
- High collateral is necessary to protect lenders if the collateral's value drops sharply.
- If the collateral value falls below the required level, the smart contract will attempt to liquidate the collateral to repurchase the lent assets.

Borrowers are incentivized to repay the loan and prevent collateral liquidation to avoid losing part of their collateral.

## Flash Loans

Flash loans are a form of cryptocurrency borrowing that does not involve collateral.

> A flash loan allows the borrower to obtain funds without any collateral, provided they repay the loan within the same transaction.

Flash loans are currently limited to those with in-depth knowledge of the ecosystem. The following is an example of how flash loans can be utilized:

1. Take out a flash loan (in tokenX) from a smart contract.
2. Swap the borrowed tokenX for tokenB on DEX1.
3. Convert tokenB to tokenC on DEX2.
4. Convert tokenC to tokenA on DEX3.
5. Repay the flash loan to the smart contract.

If any step in the transaction chain fails, the preceding steps are reverted, and the transaction fails as if it never happened.

> Anyone can use flash loans to borrow as much as needed without collateral, provided the loan is returned within the same transaction.

Flash loans enable simultaneous financial transactions: borrowing funds, making several arbitrage trades across multiple DeFi platforms, and repaying the original lender—all in one go.

## 1. Compound

Compound is a popular decentralized service for borrowing and lending cryptocurrency.

[Compound Finance](https://compound.finance/markets) loans typically require collateral, which may range from 0-90% of the borrowed asset. Each asset on Compound has a different collateral requirement.

Read: [Compound in Simple Terms](../../token_guides/en/compound.md)

## 2. Aave

[Aave](https://app.aave.com/home) provides access to both collateralized and non-collateralized flash loans.

Flash loans are sourced from a liquidity pool funded by other users. Aave charges a 0.09% fee on flash loans. For collateralized loans, a 0.01% fee of the loan amount is collected at loan origination.

Read: [Aave in Simple Terms](../../token_guides/en/aave.md)

## 3. Oasis

[Oasis](https://oasis.app/) is a DEX developed by MakerDAO that facilitates lending and borrowing of the DAI stablecoin.

- Users can borrow DAI from MakerDAO smart contracts, which create new DAI in exchange for a cryptocurrency collateral (typically 150% of the loan value).
- When DAI tokens are returned, the collateral is paid back to the borrower, and the returned DAI tokens are destroyed by the smart contract.

Read: [MakerDAO in Simple Terms](../../token_guides/en/makerdao.md)

## Risks

As with other DeFi services, there is always a risk of a hack or exploit that could drain the lending service's liquidity pool, causing lenders to lose their assets. Therefore, lenders should only commit funds they can afford to lose.