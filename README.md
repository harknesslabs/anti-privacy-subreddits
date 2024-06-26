# anti-privacy-subreddits
The following is a list of subreddits that will ban you for editing your past posts and/or delete any edit(s) you made.

This data is only currently based on the top 100 subreddits and will be expanded shortly. If you have more data, please [Submit a PR](https://github.com/harknesslabs/anti-privacy-subreddits/pulls).

[What is a anti-privacy subreddit?](#what)

| Subreddit Name | Delete Edited Posts? | Ban users who edit posts? |
| :---         |     :---:      |          ---: |
| tifu   | Yes     | no    |
| japantravel   | Yes     | ✅    |
| bayarea   | Yes     | ✅    |
|  personalfinance  | Yes     | no    |
|   business_ideas | Yes     | no    |
|  trueunpopularopinion  | Yes     | no    |
|   explainlikeimfive | Yes     | ✅    |
| productivity   | Yes     | no    |
|  askreddit  | Yes     | no    |
|  gaming  | Yes     | no    |
|  worldnews  | Yes     | no    |
|  aww  | Yes     | no    |
|  askscience  | Yes     | no    |
|  earthporn  | Yes     | no    |
| explainlikeimfive   | Yes     | no    |
|  lifeprotips  | Yes     | no    |
|  photoshopbattle  | Yes     | no    |
|  oldschoolcool  | Yes     | no    |
|  listentothis  | Yes     | no    |
|  writingprompts  | Yes     | no    |
|  wallstreetbets  | Yes     | no    |
|  Fitness  | Yes     | no    |
|   EatCheapAndHealthy | Yes     | no    |
|  tattoos  | Yes     | no    |
| nfl   | Yes     | no    |
|  mildlyinfuriating  | Yes     | no    |
|  leagueoflegends  | Yes     | no    |
|  Awwducational  | Yes     | ✅    |
|  news  | Yes     | ✅    |
|  thewitcher3  | Yes     | no    |
|  watchpeopledieinside  | Yes     | ✅    |


### what?

Some subreddits have their automod setup to automatically catch any posts that contain certain keywords, pertaining to mass-edit/deletion software.
Examples are:
Shreddit, Redact and github.com/j0be/PowerDeleteSuite

The automod setup will look for terms such as the above names or phrases like "Mass deleted" or "Mass edited" to remove your comments and/or ban you.

This is a issue because the point of editing your reddit posts and leaving them in place is so that third party "scraper" websites will typically re-scrape reddit threads and update them with the freshest data.
However, if the posts are simply deleted, the sites will not update the data and will keep the deleted comment displayed in its original form.
As such, simply deleting your posts or comments will possibly keep them alive forever on third party websites, whereas editing them has superior results for op-sec.

It is important to know that while nobody can doubt that it is incredibly annoying to search for something and then see the result being "edited, removed my data" - that we must still acknowledge that the privacy of the individual poster is more important than the general reddit experience.
Reddit, its moderators or its admins do not come before the individual users privacy when it comes to deleting or editing their past posts. The reddit experience comes second. Privacy is a hard fought right being stripped from us more and more every day and must be respected and protected lest we lose more and more of it every day. It is not hard to imagine a world where reddit, twitter or facebook simply does not allow you to even /delete/ your old posts in the future.

Users who want to protect themselves from AI Harvesting bots, stylometry attacks or other reasons have every right to anonymize their content. Subreddits punishing them is antithetical to what is best for the user itself and is a behavior that must be named and shamed.




### How can we stop this?

Letting the subreddits know that what they are doing is anti-privacy and why they stop should be priority number one. Many will be hostile and simply refer to the edits as spam and not want to engage further. Some will change their approach.

For [Redact.dev](https://redact.dev) , when a user selects to edit their posts, we are now using this github list of subreddits to send randomized edits that have no common identifying strings or tags when a post is in one of the target subreddits. 

This will prevent the automod from automatically deleting the posts. If the subreddit wants to go and delete them still, they will have to do so via manual interaction by a moderator. 

To be clear, the point of having an identifying string in the edited post saying that something was "mass edited" serves several purposes:

1: It lets future users know that this post was removed not because of something specific to the post or its contents, but because the user scrubbed all of their data.

2: It lets other users who see that post know what software they used to accomplish that goal and that it was likely performed in a automated fashion.

3: It lets moderators of the subreddit easily see that this was a automated edit and does not need further moderator action or scrutiny.

With that said, we will not tolerate subreddits abusing this string to take away from a users privacy.



### How do you verify the subreddit is anti-privacy?

The best way to verify this is to make a helpful, non-spammy post in a target subreddit. Then, verify in a new, incognito browser that your comment shows up.
Then, wait at least a day and then Edit your post to a known string that will trigger the automod, such as 

"impossible gray toothbrush hungry dam wild bag rotten intelligent future

This post was mass deleted and anonymized with Redact"

Then once again, open your comment in a new incognito window. If it still appears after 10 seconds, the subreddit is likely not hostile. If the comment is missing, its hostile because the automod immediately deleted your post.
