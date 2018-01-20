## Blocks and transactions

### Get Block Header
```
steem.api.getBlockHeader(blockNum, function(err, result) {
  console.log(err, result);
});
```
### Get Block
```
steem.api.getBlock(blockNum, function(err, result) {
  console.log(err, result);
});
```
### Get State
```
steem.api.getState(path, function(err, result) {
  console.log(err, result);
});
```
### Get Trending Categories
```
steem.api.getTrendingCategories(after, limit, function(err, result) {
  console.log(err, result);
});
```
### Get Best Categories
```
steem.api.getBestCategories(after, limit, function(err, result) {
  console.log(err, result);
});
```
### Get Active Categories
```
steem.api.getActiveCategories(after, limit, function(err, result) {
  console.log(err, result);
});
```
### Get Recent Categories
```
steem.api.getRecentCategories(after, limit, function(err, result) {
  console.log(err, result);
});
```
