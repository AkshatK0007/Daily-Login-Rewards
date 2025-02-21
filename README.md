# Daily Login Rewards Smart Contract

This is a simple Solidity smart contract that rewards users with tokens for logging in daily. The contract ensures that users can only log in once per day and accumulate rewards over time.

## Features
- Users earn tokens for daily check-ins.
- Rewards accumulate daily and can be checked anytime.
- The contract ensures that users cannot claim multiple times within 24 hours.
- Secure and gas-efficient logic.

## Deployed Address
This smart contract is deployed on the Edu Chain at the following address:
```
0x0eA8C6783b7710234f3c7565e7eF6C1528f898e0
```

## Functions
### `login()`
- Allows users to log in and receive daily token rewards.
- Ensures that a user can only log in once every 24 hours.

### `checkRewards(address user) -> uint256`
- Returns the total tokens accumulated by the given address.

## Usage
1. Call the `login()` function once per day to claim rewards.
2. Use `checkRewards(your_address)` to view your accumulated token rewards.

## License
This project is open-source and free to use.

