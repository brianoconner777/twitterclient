# kayakotwitterclient
Kayako Challenge 

A simple Twitter API client in PHP. This client simply has to fetch and display Tweets that 
  a) Have been re-Tweeted at least once and 
  b) Contain the hashtag #custserv
 
### Feature 
  Infinite scroll to fetch older tweets 
  
### Future work
  1. The website can be made genric by adding a toolbar where any user can select: <br>
     1. Hashtag they want to search <br>
     2. Minimum number of retweets each post should have <br>
     3. Date time between which the post is made etc. <br>
     The idea basically is to make this a useful website for someone, currently it just serves the problem statement given by kayako's team.
  2. Tweets can be made more elegent by adding actual link to tweet-owner profile, can display his pictures and all those sorts of things. 
  3. Currently there is no cache support as it would have been an overengineering to have cache support here. But yes, we can add cache support using Redis.
  
### Installation guide 
  1. Download/ Clone this project.
  2. When you are inside the document root, run 'composer update' command. This command will download all the project dependecies. 
  3. Generate your Api secrets from Twitter website. 
  4. Once you have your api secrets, add them to 'app/config/config.sample.php'
  5. Rename the file to config.php
  6. Download Xampp.
  7. Place the folder inside htdocs.
  8. Once the xampp server is running go to: http://localhost/Twitter-Client/
  9. Boom: tweets will appear. 
  
### Publicly accessible link::
  https://kayakotwitterclient.herokuapp.com/
  


