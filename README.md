Final Project: Upgrade UniswapV2

Name: Dheeraj Nalubolu
Email: nalubolu.d@northeastern.edu
NUID: 002709344

UniswapV2 was written three years ago and uses outdated versions of Solidity tools
Project goals:
   Achieve deep knowledge of the UniswapV2 implementation
   Learn Foundry, the next generation ethereum development environment

Resources:
Class Notes (written by Jichu Wang, a former student at NEU).
Official Uniswap Implementation
Programming DeFi: Uniswap V2

UniswapV2 code:
https://github.com/Uniswap/v2-core
https://github.com/Uniswap/v2-periphery

Notes:
The original code had the core and periphery contracts in different repos. We recommend combining them into a single repo to simplify development, and copying libraries rather than using package management.
UniswapV2Router01 should not be included.
Upgrade the UniswapV2 code to the latest Solidity version that Foundry supports.
Write Solidity tests that achieve >95% line coverage for each of the following contracts:
   UniswapV2Router02
   UniswapV2Pair
   UniswapV2Factory
Generate and commit a line coverage report to assess the quality of your tests