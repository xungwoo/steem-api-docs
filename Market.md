## Market

### Get Order Book
```
steem.api.getOrderBook(limit, function(err, result) {
  console.log(err, result);
});
```
### Get Open Orders
```
steem.api.getOpenOrders(owner, function(err, result) {
  console.log(err, result);
});
```
### Get Liquidity Queue
```
steem.api.getLiquidityQueue(startAccount, limit, function(err, result) {
  console.log(err, result);
});
```
