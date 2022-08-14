# twitter-follower-increasing-bot
This is the code for a Twitter follower increasing bot that uses the follow / unfollow method described by Mario Filho here. (https://forecastegy.com/posts/how-i-used-machine-learning-to-get-20000-real-followers-on-twitter/)

To use this notebook:
1. Fill in your username and password in cell 3
2. Set your path for chrome driver in Cell 4
3. Set the path for your unfollowing list

Functions:
twitter_login(username, password): Logs you into your Twitter Account
retrieve_followers(username): Returns a list of followers for a given username
retrieve_following(username): Returns a list of accounts followed for a given username
unfollow_list(username): Returns a list of accounts that are followed by the user but are not following back
get_user_information(username): Returns a list containing "Username", "Followers", "Following", "Join Date", "Work", "Location", "Website", "Bio", "Birthday" for a given username
follow_from_list(accounts): Follows all the accounts that are given in the list if they match the specific criteria
unfollow_from_list(unfollowing_list): Unfollows all the accounts that are given in the list and saves all the unfollowed accounts into the CSV file 

Please be careful while using this code and remember to leave at least 1-2 days between following and unfollowing accounts, otherwise, you will end up getting shadowbanned on Twitter, i.e, you will not be able to follow or unfollow anyone for 3 days.


Please Note: This bot was purely built for fun and research. It is not the author's responsibility how you use this code.
