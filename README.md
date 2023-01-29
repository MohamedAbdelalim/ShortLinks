# ShortLinks


Heroku link :https://appapp.herokuapp.com/
And https://appapp.herokuapp.com/shortlinks for the post requests

<h2>Use cases</h2>

Postman documentation:  https://documenter.getpostman.com/view/14663036/2s8ZDczfMy 

Reuest:
{
  "ios": "http://example.com/android",
  "android": "http://example.com/android",
  "web": "http://example.com/android"
}

Response:
{
    "slug": "xmXyIgu5"
}
Request:
{
  "slug": "firsttest",  
  "ios": "http://example.com/android",
  "android": "http://example.com/android",
  "web": "http://example.com/android"
}
Response:
{
    "slug": "firsttest"
}

Request:
{
  "slug": "test",  
  "ios": "http://example.com/android",
  "android": "http://example.com/android",
  "web": "http://example.com/android"
}
Response:
{
    "error": "Slug already taken"
}

Request:
{
  "slug": "firsttest",  
 
  "android": "http://example.com/android",
  "web": "http://example.com/android"
}
Response:
{
    "error": "Missing required targets (ios, android, web) in request body"
}
<br/>

Firebase Collection : https://drive.google.com/file/d/1oIb0430MfxiM6VMvPpZ9UzzyBGXqLNfw/view?usp=sharing

The app work with docker but only localy but faced issues with heroku

