    __    __  ______  __________ 
   / /   / / / / __ \/ ____/ __ \
  / /   / / / / / / / __/ / /_/ /
 / /___/ /_/ / /_/ / /___/ _, _/ 
/_____/\____/_____/_____/_/ |_|

LUDER PROTOCOL v1.0

Token protocol with automatic lottery system for holders.

## About Luder

Luder Protocol is a prototype token with a decentralized and automated lottery dynamics within the contract itself. This implementation is carried out on the Binance Smart Chain network following the BEP-20 standard.

## How does $LUDER work?

The token contract charges a tax for each purchase (6%) or sale (9%) transaction on the DEX, then it swaps to BNB and sends a corresponding percentage to a subcontract that is responsible for accumulating the lottery prizes, when the accumulated amount in this subcontract equals or exceeds 0.3 BNB, the token contract executes the lottery function and chooses an address, randomly, of a $LUDER token holder who has the minimum amount of tokens to participate in the lottery (100,000 $LUDER) and sends the funds accumulated in the lottery subcontract to them.

## Powered by Chainlink

The Luder Protocol lottery system uses Chainlink's VRF v2 technology to randomly select the winners of the automated lottery.

Chainlink's VRF technology allows for the generation of randomness within a smart contract, in this case to ensure that the results of the lottery are unpredictable and fair. This means that Luder Protocol participants can be sure that they have the same chance of winning.

In addition, by using Chainlink's VRF technology, Luder Protocol takes measures to ensure the transparency and reliability of the lottery system. All results and randomness seeds are verifiable and stored in public variables within the token contract, which means that anyone can verify the randomness of the results at any time.
