# Apple stocks and the prices
Write an efficient function that takes stock_prices and returns the best profit I could have made from one purchase and one sale of one share of Apple stock yesterday.

For example:

  stock_prices = [10, 7, 5, 8, 11, 9]

get_max_profit(stock_prices)
# Returns 6 (buying for $5 and selling for $11)
No "shorting"—you need to buy before you can sell. Also, you can't buy and sell in the same time step—at least 1 minute has to pass.
First, You need to know how much money could have made yesterday if  trading  was done  for Apple stocks all day.

So ,take Apple's stock prices from yesterday and put them in a list called stock_prices, where:

1.The indices are the time (in minutes) past trade opening time, which was 9:30am local time.
2.The values are the price (in US dollars) of one share of Apple stock at that time.

So if the stock cost $500 at 10:30am, that means stock_prices[60] = 500.
Link for the source of the question:https://www.interviewcake.com/question/python3/stock-price
