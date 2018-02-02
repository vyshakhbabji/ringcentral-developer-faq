`I'm interested in ETLing some of our data out of Ring Central. The 
whole app sandbox to production seems like overkill for what amounts to a 
few Python scripts that are GET requests to various endpoints. Furthermore, 
our sandbox env doesn't have any actual data in them so it's difficult to 
actually finish the scripts and test them out. Am I missing something? Can 
you just shift my app to production mode so I don't have to jump through 
the hoops?`

Please refer to this article : https://devcommunity.ringcentral.com/ringcentraldev/topics/production-access-request-criteria

For generating data: 
You could write your test app similar to this in your own programming language 
https://github.com/vyshakhbabji/ringcentral-call-log-record-generator-app