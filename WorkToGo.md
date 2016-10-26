#Work To Go

## Backtester

## Database of prices

## Cost Function

## Network Setup

## Network Training

## Agent
This is the "Policy Network" that will take the state of the market and decide what to do, BUY / SELL / HOLD.  To start this will be a 2 layer fully connected NN the produces a probability of action.  This will likely be using a sigmoid function to provide non-linearity and bound the output between [0,1]
