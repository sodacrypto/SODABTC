SODABTC:

This smart contract mints and distributes SODABTC between borrowers who have provided Bitcoin (BTC) as a collateral to take out a loan on SODA. Also it burns SODABTC after the borrower pays back the loan and receives their collateral in Bitcoins (BTC) back.

Borrowing:

In order to borrow cryptoassets on SODA the user needs to provide Bitcoins (BTC) as a collateral. The collateral is a guarantee of the borrower’s ability to repay a loan. One cannot borrow funds on SODA without having provided collateral. In addition, the user needs to have a MetaMask Dapp browser to receive and use borrowed cryptoassets (not your keys, not your crypto). Early SODA versions will allow users to borrow Ethereum-based cryptoassets (ERC-20).

Borrowing Procedure:

The borrower visits https://www.soda.network website to interact with SODA. To begin, they need to connect a MetaMask account in order to request the loan using SODA smart contracts. After connecting MetaMask, the user converts their Bitcoins to SODABTC (ERC-20) in order to deposit them into the smart contract. The user sends their Bitcoins to the unique Bitcoin-address generated by the BitGo system. It is a multi-signature hot wallet managed by the SODA Foundation. As the early SODA versions will be experimental, the borrowers should use the DAO at their own risk and do not deposit more Bitcoins (BTC) than they can afford to lose. Multi-sig wallets are integrated into the workflow of the SODA borrowing process.

Before sending the collateral, the user can calculate the desired loan amount and the required size of collateral for receiving a loan, selecting the loan period and looking at the end numbers before converting their Bitcoins (BTC) to SODABTC. 

Required collateral in Bitcoins (BTC) is 140% in dollar equivalent of the loan.

After sending Bitcoins (BTC) to the multi-sig hot wallet, the user needs to wait for the transaction to be confirmed by miners. After transaction is confirmed, they will receive SODABTC (ERC-20) to their Ethereum-address in MetaMask that was used for connecting to SODA in the previous step. SODABTC is minted in 1:1 proportion to the amount of Bitcoins (BTC) that were sent to the multi-sig hot wallet.

The user will see that the balance of SODABTC has changed and now they can provide them as a collateral into the SODA smart contract from the account page: https://www.soda.network/account. The user finally selects the loan amount, length of period and initiates the loan issuance while depositing the collateral. They select loan terms on the SODA interface and deposit SODABTC.

After initiating the loan issuance and sending SODABTC to the smart contract, the user needs to wait for the transaction to be confirmed by miners. When SODABTC are sent to the smart contract, SODA uses oracle to get the price info of the Bitcoin (BTC) and to integrate it into the smart contract. The price data will be integrated into the smart contract with two purposes: first, for issuing a loan and sending it to the user from the credit pool smart contract. Second, for setting a liquidation price. 

The collateral will be liquidated should it’s price fall to 110% of the loan amount.

Say, the collateral provided is 1.4 BTC at the price of Bitcoin (BTC): $10,000. The total collateral’s dollar equivalent is $14,000. With the collateral provided for $14,000, the issued loan will be for $10,000 in cryptoasset. These two parameters – initial price of Bitcoin at the moment of issue and the liquidation price – are recorded in the transaction of issuing the loan and cannot be reversed or deleted.

When the collateral is received from the user, and the oracle integrates the price data to the smart contract, the loan is finally issued and sent to the user’s MetaMask account. The balance of the borrowed cryptoasset will be displayed on the SODA interface as well as in their MetaMask account. Borrowed funds are now in the user’s hands. SODA interfaces can be used for informational purposes to manage a loan.

To repay a loan the user sends the cryptoasset of the same amount that they previously borrowed to the smart contract. Following that, they receive SODABTC and can now convert them to Bitcoins and receive them back to their Bitcoin-address.
