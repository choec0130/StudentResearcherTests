from bs4 import BeautifulSoup
import urllib.request

#use urllib module to get script from url
page_script = urllib.request.urlopen('https://s3-us-west-1.amazonaws.com/ra-training/test1.html')

#parse HTML and make readable
parsedText = BeautifulSoup(page_script, 'html.parser')
myText = parsedText.prettify()
