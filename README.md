# Summarizer

Smmrzr is a web application that will allow a user to summarize any text composition whether that be a news article or a story.

## Why make a summarizer?
Time is of the essence to everyone. Shrinking a news article for example by 50%+ can save users minutes or hours depending on how many articles they read in any given period. Understandably, the authors and editors of a composition want their works to be read in full. Many readers, however, want a quick summary highlighting the main ideas and the conclusion of the writing.

There are also education and health benefits associated with shortening text and making the points of said text very evident.

## Design
[✓] The design of our web app should be simple and intuitive. It should also be easy on the eyes as we anticipate many people will be using it at night right before bedtime. 

[✓] The web app will start by prompting the user to sign up and login. Once this process is completed, the user can begin to use the application. The user will give the application some text or a URL and then press ‘Summarize.’ The application will print out the summary on a card like structure. When the user is finished reading the summary, there will be an option for them to summarize another piece of writing. This will start the entire process over. 
![Proposal Flowchart](https://code2flow.com/vQxmbN.png)

## Functionality
[✓] Our web app takes in a url and prints out the summary on the main card. It then stores the summary in a database. Summaries can be saved if the logged in user wants to access them in the future.

~~The web app will have multiple input fields that will take in text or a URL.~~

[✓] Signup/login procedures will be handled by a [backend server](https://github.com/cgburgess/comp426-backend) after we incorporate its functionality into our project.

[✓] [SMMRY API](https://smmry.com/api) used to summarize the given input. 


## Video
[✓] Identify your target user/customer?
- People that have difficulty focusing for long periods of time and people that don’t have time to read full web articles. In general we think our app will be useful for anyone consuming news via the web.

[✓] Identify the issue that your app solves? 
- Our app reduces that amount of time needed to read and conclude key information from a web article.

[✓] Explain how your app solves the problem?
- Our app utilizes the SMMRY API to summarize text on a webpage supplied by the user. We made a full custom route utilizing no pre-built methods. This custom route has post and get methods for storing the data and retrieving the data. We created this route after getting CORS errors. One positive aspect of the custom route is that it improves the security across our app.

[✓] Demonstrate the main functionality of your website/product?
- signup, login, logout, delete account, summarize

[Video](https://youtube.com/) video on YouTube.