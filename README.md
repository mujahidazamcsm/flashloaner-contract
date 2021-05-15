# flashloaner-contract
Solidity smart contracts that operate arbitrages between Sushiswap and Uniswap
Installation
This project uses truffle or brownie for compilation.

truffle instructions
This project uses sqlite3 which is not supported uniformly across node versions.

install nvm
close and reopen terminal
nvm install 13 # install version 13 of node which is latest compatible with sqlite
nvm use 13
cd <this-repo>
npm install -g
truffle compile
If you have issues delete the node_modules folder in this dir and npm install -g again
