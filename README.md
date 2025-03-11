Description

This repository contains a smart contract lottery inspired by Cyfrin Updraft but designed for profit, similar to real-world lotteries. Unlike the standard implementation, this contract retains 10% of the collected funds for the deployer, making it a sustainable and profitable lottery system.

Additionally, the original course did not provide an integration test, so I implemented one myself to verify the full workflow, from entering the lottery to selecting a winner.

Features

Fair Random Winner Selection: Uses Chainlink VRF for provable randomness.
Profit Mechanism: 10% of the lottery pool is retained by the deployer.
Automated Upkeep: Uses Chainlink Keepers to automate winner selection.
Comprehensive Testing: Includes unit tests and a full integration test.