# foodtruckproto

# Getting started
Have to install selenium (python package) for the current twitterscraper. I did
it via `pip install selenium`. You need python 3 tho.

The address parser currently is `pip install usaddress` which I got from here: 
https://github.com/datamade/usaddress.

Lastly, you will need to download the chrome browser as well as the chrome 
driver (https://chromedriver.storage.googleapis.com/index.html?path=2.41/), and then put the chrome driver in your PATH that python looks in.

## TODO:
### Current Goals
- [ ] Figure out how to parse addresses appropriately
- [ ] Figure out how to parse dates appropriately

### Future Goals
- [ ] Create a system that stores previous identified locations, which will help
to quickly identify locations in tweets that are not in traditional format
- [ ] Figure out a way to pair addresses and times
- [ ] Identify other potential events like promotions and contests
- [ ] Create a twitter scraper class with useful functions
- [ ] Make a list of food trucks to test on

### Completed Goals
- [x] Parse times out of tweets

## Food trucks considered only in LA
KogiBBQ, grlldcheesetruk, NoMadTruckLA, JogasakiBurrito, LobstaTruck