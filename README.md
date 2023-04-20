Final Project: Upgrade UniswapV2<br>

Name: Dheeraj Nalubolu<br>
Email: nalubolu.d@northeastern.edu<br>
NUID: 002709344<br>

UniswapV2 was written three years ago and uses outdated versions of Solidity tools<br>
Project goals:<br>
   Achieve deep knowledge of the UniswapV2 implementation<br>
   Learn Foundry, the next generation ethereum development environment<br>

Resources:<br>
Class Notes (written by Jichu Wang, a former student at NEU).<br>
Official Uniswap Implementation<br>
Programming DeFi: Uniswap V2<br>

UniswapV2 code:<br>
https://github.com/Uniswap/v2-core<br>
https://github.com/Uniswap/v2-periphery<br>

Notes:<br>
The original code had the core and periphery contracts in different repos. We recommend combining them into a single repo to simplify development, and copying libraries rather than using package management.<br>
UniswapV2Router01 should not be included.<br>
Upgrade the UniswapV2 code to the latest Solidity version that Foundry supports.<br>

Write Solidity tests that achieve >95% line coverage for each of the following contracts:<br>
   UniswapV2Router02<br>
   UniswapV2Pair<br>
   UniswapV2Factory<br>
Generate and commit a line coverage report to assess the quality of your tests<br>
