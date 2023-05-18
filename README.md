# Newsapi_Slack
Functions

**Slack Interacive trigger**

	-/newsapi
  
    	Search for specific keyword and shows the news article for that.
    
	-/newsgpt
  
    	Shows results of specified news tranlated (deepl) and summarized by chatgpt.
      
**Setup**

	1. Create a slack bot in api.slack
	
	2. Obtain signing secret (SLACK_SIGNING_SECRET) and bot token (SLACK_BOT_TOKEN). 
	Bot token can be obtained from OAuth & Permissions section after adding scopes.
	
	3. Create /newsapi, /newsgpt slash commmand.  
	URL will be Azure webapp url. (E.g- https://slackbotprod.azurewebsites.net/mp3_trigger)
	
	4. Add to workspace.
	
	4. Set up a webapp in Azure and connect to the github repo. 
	Add the environment secrets (SLACK_BOT_TOKEN, SLACK_SIGNING_SECRET, OPENAI_API_KEY, DEEPL_API, NEWS_API_KEY)
