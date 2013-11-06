heroku-twitter
==============

Heroku app to handle twitterfeed for Social Feed https://github.com/mikaelbr/SocialFeed.js

## Explanation
This is based on the example found at https://github.com/mikaelbr/SocialFeed.js/tree/master/example/Twitter and as pointed out in example, should be used with a heroku app. 

Installation
--------------
Create you heroku app at https://id.heroku.com/ and download the git repo.
Copy the files from this repo into your heroku app repo and edit *web.js* and add consumer_key, consumer_secret, access_toke, access_token_secret and username you got when you registred an application from https://dev.twitter.com/
```sh
 , T = new Twit({
      consumer_key:         ''
    , consumer_secret:      ''
    , access_token:         ''
    , access_token_secret:  ''
  })
  , username = ''
  ;
```
Commit and push to repo and you will find a url under settings for your heroku app called Domains. Point your socialfeed request to that url


  [daniel andreasson]: http://danjuls.se/
  [@danjuls_]: http://twitter.com/danjuls_
  [herouku]: http://twitter.com/tjholowaychuk
  [express]: https://id.heroku.com/
  
 
