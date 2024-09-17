| Name             | Type                     | Slot | Offset | Bytes | Contract                                                                 |
|------------------|--------------------------|------|--------|-------|--------------------------------------------------------------------------|
| _initialized     | uint8                    | 0    | 0      | 1     | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| _initializing    | bool                     | 0    | 1      | 1     | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| pauserRegistry   | contract IPauserRegistry | 0    | 2      | 20    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| _paused          | uint256                  | 1    | 0      | 32    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| __gap            | uint256[48]              | 2    | 0      | 1536  | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| underlyingToken  | contract IERC20          | 50   | 0      | 20    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| totalShares      | uint256                  | 51   | 0      | 32    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| __gap            | uint256[48]              | 52   | 0      | 1536  | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| maxPerDeposit    | uint256                  | 100  | 0      | 32    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| maxTotalDeposits | uint256                  | 101  | 0      | 32    | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |
| __gap            | uint256[48]              | 102  | 0      | 1536  | src/contracts/strategies/StrategyBaseTVLLimits.sol:StrategyBaseTVLLimits |