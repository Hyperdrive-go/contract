# Hyperdrive smart contract 
*Contract v1 fork from quixotic exchange, suitable for curent backend-api
### Read contract
- calculateCurrentPrice
- getRoyaltyPayoutAddress
- getRoyaltyPayoutRate
- isOrderCancelled
- owner
- paused

### Write contract
- cancelBuyOrder
- cancelPreviousSellOrders
- fillBuyOrder
- fillDutchAuctionOrder
- fillSellOrder
- pause
- renounceOwnership
- setMakerWallet
- setRoyalty
- setWethContract
- transferOwnership
- unpause
- withdraw

### Class function
- interface IERC165
- interface IERC721
- interface IERC1155
- interface IERC20
- library ERC165Checker
- library Strings
- library ECDSA
- library Address
- interface IRoyaltyRegistry
- interface ICancellationRegistry

@TODO *Contract v2 using seaport & proxy
