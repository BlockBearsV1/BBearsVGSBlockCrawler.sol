# BBearsVGSBlockCrawler.sol
BlockBearsVGS Block-Crawler

```
# BBearsVGSBlockCrawler

The `BBearsVGSBlockCrawler` contract is a Solidity smart contract that allows the contract owner to adjust the mining reward amount and claim their own rewards.

## Features

- Adjust the mining reward amount
- Claim mining rewards

## Getting Started

### Prerequisites

- Solidity development environment
- Truffle framework (optional)

### Deployment

1. Deploy the `BBearsVGSBlockCrawler` contract to a supported Ethereum network (e.g., Ganache, Ropsten, etc.).

2. Once deployed, the contract owner can adjust the mining reward amount using the `adjustReward` function.

3. The contract owner can claim their own rewards by calling the `claimMiningReward` function.

## Usage

### adjustReward

Adjusts the mining reward amount.

```solidity
function adjustReward(uint256 newReward) external onlyOwner
```

- Parameters:
  - `newReward`: The new mining reward amount.

### claimMiningReward

Claims the mining reward by the contract owner.

```solidity
function claimMiningReward() external onlyOwner
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
