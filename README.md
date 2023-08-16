# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery

## What do we want it to do?

1. Allow users to enter the lottery by paying for a ticket
    1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programmatically
3. Using Chainlink VRF & Chainliink Automation
    1. We will use Chainlink VRF to generate a true, proveably random number (outside of the blockchain)
    2. We will use Chainlink Automation time-based trigger, to trigger the draw

## Tests!
