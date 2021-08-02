# BollywodMovieRecommandationsystem-using-sentiment-analysis

Required libraries:
      Flask,
      gunicorn,
      MarkupSafe,
      numpy,
      scipy,
      nltk,
      scikit-learn,
      pandas,
      jsonschema,
      tmdbv3api,
      lxml,
      urllib3,
      requests,
      pickleshare.
 
We need an api , you can get API key from https://www.themoviedb.org/. (follow the steps given in this site to get API key)
# Steps to Run project

Clone or download this repository to your local machine
Installed Required libraries: 
copy this code into yoy main.py and replace your api key.

      from tmdbv3api import Movie

      tmdb = TMDb()
      tmdb.api_key = 'API Key'
      

Replace YOUR_API_KEY in both the places (line no. 15 and 29) of static/recommend.js file and hit save.

Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.

Go to your browser and type http://127.0.0.1:5000/ in the address bar

# Used Algorithm for sentiment analysis
## Multinomial naive Bayes ##
accuracy score :97.47109826589595
