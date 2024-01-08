# Introduction
WeRateDogs is a Twitter account that posts and rates pictures of dogs. These ratings often are not serious and have numerators that are greater than the denominators. In this analysis, I mostly focus on wrangling WeRateDogs's Twitter archive through August 1, 2017. Most of the necessary Twitter data has been provided by Udacity and includes information on each post, as well as details on each dog such as the name, rating, and stage (whether the dog is a doggo, floofer, pupper, or puppo). See below for definitions on the dog stages. However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

For some people, who certainly love dogs will love to share what their dogs do. Like the majority of posts on @dog_rates or better known as WeRateDogs, dog lovers love to share photos of their dogs. Surely this is a happiness that should be shared among the dog lovers.

Have you ever heard the quote in the title,"They are Good Dogs of Brent"?, which are widely used in memes to cover people who take issue about the WeDogRate ranking system. What happened in their system is, numerator is far far bigger than the denominator. Yes, you're not heard it wrong, that was their rating system. Even the ratings reach unreasonable numbers.

WeRateDogs intended to humorously review pictures of dogs doing adorable poses. So, take it easy Brent
There are many interesting insights from their twitter post. In this article, we want to show you what we find after wrangling some data from it.

# Most common name for dog
With the count more than 900 names, dog sure has varies name. This is kind of interesting, from the detection algorithm, people tends not to share their dog name to the WeRateDogs users. Usually people only share only it's stage or type in the Twitter.
For the most common name for dog posted is Oliver, Cooper, and Charlie, each with count 10.

# Golden Retriever is the most popular dog type.
The dog which is has ranks 3 of 196 in AKC Breed Popularity is the most popular among WeRateDog posts. Has total retweet of 483833 and favorite of 1681869 outperforming other dogs breed.

#  Dog Rating
If we sum all the y the WeRateDog post, we can get dog type total rating. As we can guess, more retweet is more rating that it get. And still, the number one is our beloved golden retriever. The most rated dog is golden_retriever with rate 169.76818181818166 and the lowest rated dog is loggerhead with rate 0.3.

# Most and lowest average rating among all
Then if we average the rating, we get the clumber is the highest among all. Our lovely golden isn't even in the top five. The most average rated dog is clumber with average rate 2.7, and he lowest average rated dog is loggerhead with average rate 0.3.

#Requirements
.Jupyter Notebook
.Pandas
.Numpy
.Requests
.Tweepy
.json
.Matplotlib
.Scipy
.Twitter API
