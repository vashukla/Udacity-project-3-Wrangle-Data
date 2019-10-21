udacity-wrangle-and-analyze-data
Udacity Data Analyst Term 2 Project 3: Wrangle and Analyze Data
Introduction
Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it. This is called data wrangling.

The dataset that was wrangled (and analyzed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

How to run the script
You need to be able to work in a Jupyter Notebook on your computer.The following packages (libraries) need to be installed. You can install these packages via conda or pip:

pandas
NumPy
requests
tweepy
json
Files
act_report.html
act_report.ipynb
dogtionary-combined.png
image-predictions.tsv
notebook.tex
tweet_json.txt
tweet_json2.txt
tweets_data_2.csv
tweets_data.csv
twitter_archive_master.csv
twitter-archive-enhanced.csv
wrangle_act.ipynb
wrangle_report.html
wrangle_report.ipynb
Findings
Our chart indicates that by far Golden Retriever receive the most favorite count and is thus, the most favore dog breed on WeRateDogs. Golden Retriever is followed by the also very popular breeds of Labrador Retriever and Pembroke. On the other hand, it is not surprising to see this situation as Golden Retriever also account for the most tweets (150), followed by Labrador Retriever (100) and Pembroke (88). Having a look on the mean Favorite Count, the situation changes drastically. From this angle, the data indicates that Saluki, French Bulldong and Black T Tan Coonhound are the most popular dog breeds on WeRateDogs.

Our data set indicate that depending on the Stage of a Dog, a post seem to receive different mean favorite counts. The bar chart indicates that Puppo, Blep and Doggos seem to receive more favorites than Floffer and Pupper do. In Average, Puppo and Blep receive more than 20'000 like counts per tweet. Doggos account for about 17500 favorite counts per tweat, wheareas Floofer only receive about 12800 favorite counts and Pupper only about 6800.

In comparison to our public statistics, it is interesting to see that different breeds are rated the highest from WeRateDogs itself. Here, Pomernian, Saluki, Tibetian Mastiff, Briand and Border Terier achieve the highest scores. This is a very interesting fact, considering Saluki being also among the populars in the previous analyses. It indicates that the popularity of dog breeds are different among the WeRateDogs audiance and the channel owners.
