# Link_Shortner
#Link Shortner

# 1.pip install pyshorteners
# 1.pip install pyperclip

import pyshorteners

#Taking long url as i/p from the user
url = input("Enter the url: \n")

def shortenurl(url):
    # created an object of this pyshortener
    s = pyshorteners.Shortener()
    print("Shorten url is: ")
    # Processing the url into short url and printing the url and printing shorten url
    print(s.tinyurl.short(url))

#function call
shortenurl(url)
