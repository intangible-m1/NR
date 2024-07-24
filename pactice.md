import requests 
from bs4 import BeautifulSoup 
url = "https://www.forbes.com/sites/adrianbridgwater/2019/04/15/what-drove-the-ai-renaissance/?sh=55268aa01f25"
response = requests.get(url)
soup = BeautifulSoup(response.text, 'html.parser')
