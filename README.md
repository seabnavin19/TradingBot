"# TradingBot" 
Past experience
Running some models to predict the price
LSTM , RNN

Glossary
Strategy
Whether I should buy or sell?
Back-testing
I have Strategy A -> Is this working?
If last day is lower than today, we sell
If last day is higher than today, we buy
Steps
Prepare N-year data (3 years)
Daily
30-minute interval
Run the strategy on the data
Simulate the strategy and get the result with the prepared date
Evaluate the result


Steps
Implement
Predictive model: LSTM / RNN
Strategies based trading
etc
Testing
Backtesting


Production
Running on a real broker


Tasks
Build/implement a backtesting framework
Prepare data
Test with dummy strategy
Find some good strategies
Simple high/low
DL models
Mixtures
Maybe 10 strategies
Each strategy will vote for buy or sell
If either one gets majority, then we exec
Scenarios
I have a DL model
Run the model on the date T
Build a strategy around this model

Case
Have a model, got the prediction from Jan 1st to Jan 15th
Run the back testing for the same period
Predict $ for Jan 1st
Look up the prices 30 days before
Back testing
Dec 1st - Dec 31st => predict a price
Buy or sell


