#Work To Go

## Backtester
Include uncertainty in the stock purchase price

## Database of prices

## Cost Function
Maximize Sharpe Ratio, Also investigate penalities for frequent trades and getting all in and all out within the same day.  

## Network Setup

## Network Training

## Agent
This is the "Policy Network" that will take the state of the market and decide what to do, BUY / SELL / HOLD.  To start this will be a 2 layer fully connected NN the produces a probability of action.  This will likely be using a sigmoid function to provide non-linearity and bound the output between [0,1]
