# Machine Learning based Tweet Sentiment Analysis

Search for Tweets and download the data labeled with it's Polarity in CSV format


[![](http://i.imgur.com/H78FZUX.png)](http://i.imgur.com/H78FZUX.png)


## Development Guide (Steps)

1. Go to (https://apps.twitter.com), create development application there for API access
2. Create a virtual Environment. `virtualenv venv`
3. Activate venv. `source venv/bin/activate`
4. Install the requirements. `pip install -r requirements.txt`
5. Save the `ACCESS_TOKEN`, `ACCESS_TOKEN_SECRET`, `CONSUMER_KEY`, `CONSUMER_SECRET` as environment variables. You can follow [this](https://devcenter.heroku.com/articles/config-vars) guide for Heroku (or any other online server you wish to run this upon).
6. Change twitter username in `app.py` at `line 8` to yours(one that was used to create API access at (https://apps.twitter.com)
7. Run the server. `python app.py`


## [License MIT © Piyush Varshney](https://piyushvarshney.mit-license.org/)
