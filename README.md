# URL Schemes Store

A store of URL schemes.

## Social Networking

### WeChat
- Open: `weixin://`
- Scan: `weixin://scanqrcode`

### QQ
- Open：`mqq://`

### Weibo
- Open: `weibo://` or `sinaweibo://`
- Scan QR code: `weibo://qrcode`

### Jidian
- Open: `jidian://`
- Post: `jidian://post?text=TEXT`

### Tweetbot
- Open: `tweetbot://`
- Timeline: `tweetbot://<screenname>/timeline`
- Mentions: `tweetbot://<screenname>/mentions`
- Retweets: `tweetbot://<screenname>/retweets`
- Direct Messages: `tweetbot://<screenname>/direct_messages`
- Lists: `tweetbot://<screenname>/lists`
- Favorites: `tweetbot://<screenname>/favorites`
- Search: `tweetbot://<screenname>/search[?query=<text>&callback_url=<url>]`
- Status: `tweetbot://<screenname>/status/<tweet_id>?callback_url=<url>`
- User Profile: `tweetbot://<screenname>/user_profile/<screenname|user_id>?callback_url=<url>`
- Post: `tweetbot://<screenname>/post[?text=<text>&callback_url=<url>&in_reply_to_status_id=<tweet_id>]`
- Follow:  `tweetbot://<screenname>/follow/<screenname|user_id>`
- Unfollow:  `tweetbot://<screenname>/unfollow/<screenname|user_id>`
- Favorite:  `tweetbot://<screenname>/favorite/<tweet_id>`
- Unfavorite:  `tweetbot://<screenname>/unfavorite/<tweet_id>`
- Retweet: `tweetbot://<screenname>/retweet/<tweet_id>`
- List:  `tweetbot://<screenname>/list/<list_id>?callback_url=<url>`

### Instagram
- Open: `instagram://` or `instagram://app`
- Camera: `instagram://camera`
- Media with this ID: `instagram://media?id=MEDIA_ID`
- User with this username: `instagram://user?username=USERNAME`
- Location feed for this location ID: `instagram://location?id=LOCATION_ID`
- Tag feed for this tag: `instagram://tag?name=TAG`

## Media

### Netease Music
- Open: `orpheus://`
- Recognize music: `orpheuswidget://recognize`

## Lifestyle & Finance

### Alipay
- Open: `alipay://`
- Scan: `alipayqr://platformapi/startapp?saId=10000007`
- Payment code: `alipayqr://platformapi/startapp?saId=20000056`
- Lucky money:
`alipay://platformapi/startapp?saId=88886666`
- Create chat group:
`alipay://platformapi/startapp?appId=20000254&actionType=createGroup`

## Utilities

### Price Tag
- Open: `pricetag://`
- History: `pricetag://history`
- Favorites: `pricetag://favorites`
- Check historical price:
  + URL: `pricetag://activity?url=STORE_URL`
  + ID: `pricetag://activity?id=STORE_ID`

### Surge
- Open: `surge://`
- Start with selected configuration: `surge://start[?autoclose=true]`
- Stop current session: `surge://stop[?autoclose=true]`
- Start or stop with selected configuration: `surge://toggle[?autoclose=true]`
- Install a configuration from a URL: `surge:///install-config?url=URL`

### Shadowrocket
- Open: `shadowrocket://`
- Connect VPN: `shadowrocket://connect`
- Disconnect VPN: `shadowrocket://disconnect`
- Toggle VPN: `shadowrocket://toggle[?autoclose=yes]`

### Potatso 1
- Open: `potatso://`
- Start VPN: `potatso://on[?autoclose=true]`
- Stop VPN: `potatso://off[?autoclose=true]`
- Toggle VPN: `potatso://switch[?autoclose=true]`

*Remark: Support `x-callback-url`*

### 1Password
- Open: `onepassword://`
- Search: `onepassword://search/KEYWORD`
