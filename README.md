# Analyzing Real time twitter data 

## Description: ## 
1. Transforming realtime twitter stream and storing them in a data storage. 
2. Parsing over the tweets and derving meaning insights from it. 
3. Searching for results based on input keywords

## Analysis: ##

* Twitter Reacts 'President Trump'
   * dashboard:
https://spotfire.cloud.tibco.com/spotfire/wp/render/dyuHI9GrdEXvoWo3i1/analysis?file=/users/anagrawa/Public/twitter_reacts_trump&waid=e68zpoAeXUOuKzmQMKR5i-0420231da9tCH0&wavid=0

* Deriving people’s sentiments for the presidential candidates
   * Dashboard:
https://spotfire.cloud.tibco.com/spotfire/wp/OpenAnalysis?file=84784eb5-ded0-4cb4-aeac-23e17fbc3ada

* US states sentiments and Acitvities
   * Dashboard:
https://spotfire.cloud.tibco.com/spotfire/wp/render/QZGmidrJVAwGE15CfM/analysis?file=/users/anagrawa/Public/twitterDataAnalysis&waid=tcpVDzeF_UOtKK_qv2Vv7-1803055da5xPpJ&wavid=0

3. Results for Text search:

   

## Workflow: ##
* twitter->pipeline->load->analyze

1. Formatting the realtime twitter data : cleaning up data (encoding unicode text, initializing locations) and sotring them in MongoDB
2. Access the documents from MongoDB and transform jason data into tabular format and store extracted results in oracle database
3. Accessing the database with TIBCO Spotfire to build business intelligence dashbards
4. Ability to stream real-time twitter feed and derive analysis
5. Text search control, providing valid results based on keyword search in twitter text data.
   a. List of related tweets
   b. List of Top retweets
   c. List of top location
   d. List of related keywords, hashtags
   
   
   Screenshots:
   
