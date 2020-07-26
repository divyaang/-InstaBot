# -InstaBot

This project is divided into two parts: Part-I and Part-II.

Motivation: Your friend has opened a new Food Blogging handle on Instagram and wants to get famous. He wants to follow a lot of people so that he can get noticed quickly but it is a tedious task so he asks you to help him. As you have just learned automation using Selenium, you decided to help him by creating an Instagram Bot.

PART - I

Problem statements considered in this part include:

1. Login to your Instagram Handle
1.1 Submit with sample username and password

2. Type for “food” in search bar and print all the names of the Instagram Handles that are displayed in list after typing “food”
2.1 Note : Make sure to avoid printing hashtags

3. Searching and Opening a profile using 
3.1 Open profile of “So Delhi” 

4. Follow/Unfollow given handle - 
4.1 Open the Instagram Handle of “So Delhi”
4.2 Start following it. Print a message if you are already following
4.3 After following, unfollow the instagram handle. Print a message if you have already unfollowed.

5. Like/Unlike posts
5.1 Liking the top 30 posts of the ‘dilsefoodie'. Print message if you have already liked it.
5.2 Unliking the top 30 posts of the ‘dilsefoodie’. Print message if you have already unliked it.

6. Extract list of followers
6.1 Extract the usernames of the first 500 followers of ‘foodtalkindia’ and ‘sodelhi’.
6.2 Now print all the followers of “foodtalkindia” that you are following but those who don’t follow you.

7. Check the story of ‘coding.ninjas’. Consider the following Scenarios and print error messages accordingly -
7.1 If You have already seen the story.
7.2 Or The user has no story.
7.3 Or View the story if not yet seen.

PART - II

Problem statements considered in this part include:

1. Now your friend has followed a lot of different food bloggers, he needs to analyse the habits of these bloggers.
1.1 From the list of instagram handles you obtained when you searched ‘food’ in previous project. Open the first 10 handles and find the top 5 which have the highest number of followers
1.2 Now Find the number of posts these handles have done in the previous 3 days.
1.3 Depict this information using a suitable graph.


2. Your friend also needs a list of hashtags that he should use in his posts.
2.1 Open the 5 handles you obtained in the last question, and scrape the content of the first 10 posts of each handle.
2.2 Prepare a list of all words used in all the scraped posts and calculate the frequency of each word.
2.3 Create a csv file with two columns : the word and its frequency
2.4 Now, find the hashtags that were most popular among these bloggers
2.5 Plot a Pie Chart of the top 5 hashtags obtained and the number of times they were used by these bloggers in the scraped posts.


3. You need to also calculate average followers : likes ratio for the obtained handles.
Followers : Likes ratio is calculated as follows:
3.1 Find out the likes of the top 10 posts of the 5 handles obtained earlier.
3.2 Calculate the average likes for a handle.
3.3 Divide the average likes obtained from the number of followers of the handle to get the average followers:like ratio of each handle.
3.4 Create a bar graph to depict the above obtained information.

This Project was done as part of Data Science and Machine Learning Course offered by Coding Ninjas. 
