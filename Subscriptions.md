## Subscriptions

### Set Subscribe Callback
```
steem.api.setSubscribeCallback(callback, clearFilter, function(err, result) {
  console.log(err, result);
});
```
### Set Pending Transaction Callback
```
steem.api.setPendingTransactionCallback(cb, function(err, result) {
  console.log(err, result);
});
```
### Set Block Applied Callback
```
steem.api.setBlockAppliedCallback(cb, function(err, result) {
  console.log(err, result);
});
```
### Cancel All Subscriptions
```
steem.api.cancelAllSubscriptions(function(err, result) {
  console.log(err, result);
});
```
