# Release

## 3.0.1 - 2021-06-10

### New  Features

* **ETH network ETH max swap amount**:  When the user chooses to swap ETH to pegged ETH, the max amount will be ETH balance - estimated transfer fee; Add a reminder message of change: The estimated max amount is your ETH balance minus the estimated gas fee 
*  Add "[**Refund History**](guides/binance-bridge-history-page.md#refund-history)" to History page: With the release of Bridge V3, the refund process for the following orders between BSC and Ethereum will be automatic. Users can check the refund tx easily 

## 3.0.0 - 2021-04-27

### New  Features

* Add network
* Add Token to MetaMask
* The refund process for the following orders between BSC and Ethereum will only take about an hour from **2021/5/26 14:00PM（SGT）**:
  * Failed deposit
  * Send multiple deposits for the same order
  * Deposit after the swap becomes to 'DepositTimeout'
  * fromAddress is different from walletAddress

### Changed

* When swap tokens between BSC and Ethereum, connected network must be the same as fromNetwork
* When swap tokens between BSC and Ethereum, toAddress and walletAddress must  be the same

## 2.1.0 - 2021-01-27

### New  Features

* [Buy BNB as gas](guides/buy-bnb-as-gas.md)

## [2.0.0](https://www.binance.org/en/blog/binance-bridge-v2-release/) - 2020-12-22

### New  Features

* Switch between V1 and V2
* New UI

### Changed

* Remove "Peg-in" and "'Peg-out".

[Doc Link]()

## [1.0.0 ](https://www.binance.com/en/support/announcement/b763da0c6ace4e32bf8e65844e6c72e2)- 2020-11-06 \[Deprecated\]

### Added

* This is the first release

[Doc Link](guides/binance-bridge-v1.md)

