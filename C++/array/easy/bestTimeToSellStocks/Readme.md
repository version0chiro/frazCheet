# Questions

### Best Time to Buy and Sell Stock

You are given an array prices where prices[i] is the price of a given stock on the ith day.

You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.

Return the maximum profit you can achieve from this transaction. If you cannot achieve any profit, return 0.

| Sr.No | Input                  | Output |
| ----- | ---------------------- | ------ |
| 1     | prices = [7,1,5,3,6,4] | 5      |
| 2     | prices = [7,6,4,3,1]   | 0      |

### Explantaion:

1. Simple solution of this problem is simply to find the minimum buy price of the stock and at every point , find if the current value gives maximum profit using a simple max in built function.


2. Return the maximum profit.
