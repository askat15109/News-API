# News-API
News App
# Use the NewsAPI and the requests module to fetch the daily news 
# related to different topics.

# Go to: https://newsapi.org/ and explore the various options to build you apllication

import requests
import json

query = input("Choose the Topic : ")
url = f" https://newsapi.org/v2/everything?q={query}&apiKey=795349f6b01d4295afebed151c5b1cb9"
r = requests.get(url)
news = json.loads(r.text)
#print(news, type(news))

for article in news["articles"]:
    print(article["title"])
    print(article["description"])
    print("-------------------------------------------------------------------------------------------")
