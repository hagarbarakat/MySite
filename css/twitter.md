# Twitter API
## Rate limits
    https://developer.twitter.com/en/docs/twitter-api/v1/tweets/timelines/faq#:~:text=What%20are%20the%20new%20rate,auth%20and%20app%2Dauth%20requests

- 100,000 requests per day as a default. This is a total request limit that applies across both user-auth and app-auth requests. These limits will be on a per-application and per-endpoint basis, meaning that a single developer app can make up to 100,000 calls to each of the two endpoints during any single 24-hour period. The existing default user-auth and app-auth rate limits will not change.

### What can I do if I am impacted by this change?
- My application serves other businesses:
    Please complete the enterprise API application via this form with detailed information about your application that makes use of these endpoints.
    A Twitter representative will be in touch to discuss available options for continued access. Part of this process will include a review of your application, your use case, and a consultation of the best API solutions available to serve your needs.

### If an app makes a request to mentions or user timeline and it fails (e.g., 401 Unauthorized), will it count against the 100,000 limit?
- No. If the request fails, then it will not count against the 100,000 limit.

## Metrics 
### Twitter API v2: Early Access
- Impressions
- Retweets
- Quote Tweets	
- Likes
- Replies
- URL Link Clicks	
- User Profile Clicks	
- Video views
- Video view quartiles	
### Twitter API v1.1
    https://developer.twitter.com/en/docs/twitter-api/v1/metrics/get-tweet-engagement/overview
- Requests return a total metric for impressions and a total metric for engagements for the desired Tweets
- Limited to the following metrics: Impressions, Engagements, Favorites, Replies, Retweets, Quote Tweets, and Video Views
- Supports the ability to retrieve Impressions and Engagements metrics for Tweets created within the last 90 days using OAuth 1.0a (user context)
- Supports the ability to retrieve Favorites, Retweets, Quote Tweets, Replies, and Video Views metrics for any Tweet using OAuth 2.0 Bearer token
- The results are based on the current total of impressions and engagements at the time the request is made
- Ideal for powering a dashboard report and for calculating engagement rates across a variety of owned @handles
- Supports requesting metrics for up to 250 Tweets per request

## Direct Message API features
    https://developer.twitter.com/en/docs/twitter-api/v1/direct-messages/api-features
- Send and receive Direct Messages.
- Create messages that display for specific scenarios.
- Attach videos, images and GIFs.
- Quick replies - Prompt users for structured replies with a menu of options. - 
- Add buttons to link to websites, deep link to apps or other parts of Twitter.

