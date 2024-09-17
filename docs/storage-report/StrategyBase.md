| Name            | Type                     | Slot | Offset | Bytes | Contract                                               |
|-----------------|--------------------------|------|--------|-------|--------------------------------------------------------|
| _initialized    | uint8                    | 0    | 0      | 1     | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| _initializing   | bool                     | 0    | 1      | 1     | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| pauserRegistry  | contract IPauserRegistry | 0    | 2      | 20    | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| _paused         | uint256                  | 1    | 0      | 32    | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| __gap           | uint256[48]              | 2    | 0      | 1536  | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| underlyingToken | contract IERC20          | 50   | 0      | 20    | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| totalShares     | uint256                  | 51   | 0      | 32    | src/contracts/strategies/StrategyBase.sol:StrategyBase |
| __gap           | uint256[48]              | 52   | 0      | 1536  | src/contracts/strategies/StrategyBase.sol:StrategyBase |