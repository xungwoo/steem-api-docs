## Tags

### Get Trending Tags
```
steem.api.getTrendingTags(afterTag, limit, function(err, result) {
  console.log(err, result);
});


// result - trending 값으로 sorting, afterTag 포함 후순위부터 
[
  {
    name: 'kr',
    total_payouts: '1681473.686 SBD',
    net_votes: 161688,
    top_posts: 13729,
    comments: 88651,
    trending: '323065260'
  },
  {
    name: 'art',
    total_payouts: '2446881.164 SBD',
    net_votes: 552521,
    top_posts: 38905,
    comments: 33238,
    trending: '226958996'
  },
  ...
  {
    name: 'steem',
    total_payouts: '3611589.498 SBD',
    net_votes: 293050,
    top_posts: 22487,
    comments: 21010,
    trending: '136751067'
  }
]
```
### Get Discussions By Trending
```
steem.api.getDiscussionsByTrending(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Created
```
steem.api.getDiscussionsByCreated(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Active
```
steem.api.getDiscussionsByActive(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Cashout
```
steem.api.getDiscussionsByCashout(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Payout
```
steem.api.getDiscussionsByPayout(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Votes
```
steem.api.getDiscussionsByVotes(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Children
```
steem.api.getDiscussionsByChildren(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Hot
```
steem.api.getDiscussionsByHot(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Feed
```
steem.api.getDiscussionsByFeed(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Blog
```
steem.api.getDiscussionsByBlog(query, function(err, result) {
  console.log(err, result);
});
```
### Get Discussions By Comments
```
steem.api.getDiscussionsByComments(query, function(err, result) {
  console.log(err, result);
});
```
