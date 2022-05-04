1. swap ETH for wETH
2. deposit some ETH (wETH) into Aave
3. borrow some asset with the ETH collateral
    a. sell that borrowed asset (short selling)
4. repay everything back

Testing:
    Integration test: Kovan
    Unit test: Mainnet-fork (since no oracles and all contracts contained w/ Aave)