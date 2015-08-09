# Using Postman to Explore aWhere's APIs

Start exploring our APIs without a lot of code by plugging these collections into your [Postman](http://www.getpostman.com) application. There is a preconfigured API call for each of the endpoints we currently have open, and Postman will even handle the security token for you. 

## Installing

We provide two files to import into Postman: 

`awhere.postman_environment`
This file sets up an Environment in Postman, where you can enter your API key and secret. 

`aWhereV1APIs.json.postman_collection`
These are the prebuilt API requests. 

First install the environment from the Environments menu. Enter your API Key and Secret in the environmental variables and then be sure the "aWhere" environment is selected. 

Then you can import the collection itself, which will appear under the Collections menu in the left pane. 

For more details on how to get started with Postman, read our help guide available on the [aWhere Developer Community](http://developer.awhere.com/integration/postman).

## Using 

Each API call has an introduction that describes how the API is used and what else you can do with it. 

The most important thing is to make sure you have an OAuth Access Token saved to the Postman environment before making the regular API calls. 

1. First make sure you've entered your API Key and Secret in the Environment, described above and on the [ADC](http://developer.awhere.com/integration/postman).
2. Then execute the Get a Token request from the collection. 

The Get a Token request will take your API key and secret and use them to generate a token; then Postman will save that token to the environment and use it automatically in the rest of the API requests. Of course, you can explore the "Headers" tab to see how to use the HTTP Authentication headers in both cases. Explore away! These are GET requests only and you can't really hurt anything. 

_Note: the token will expire after an hour. So you only need to run the Get a Token request once unless it's been more than an hour since the last time._

## Help

If you need help with Postman, check out the [Postman documentation](https://www.getpostman.com/docs).

If you need help with the Collection we've provided or the API calls, then ask a question in our [Community Q&A Forum](http://developer.awhere.com/forums). 