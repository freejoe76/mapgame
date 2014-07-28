# Map Game
Make a "Where Is X (Country / City) On The Map?" game.

# Getting Started
# Usage
Here's how you would create a Map Game for your site:
...

## Yes! I Want A Dev Environment
First, you need a webserver running on your computer. We're running a webserver with a dummy article on it so we can test against publishing these maps in articles. May want to revisit that decision.

1. Check out this repo. `git clone git@github.com:freejoe76/mapgame.git`
1. Get the submodule information in there: `git submodule update --init`
1. Symlink your testing directory into the place your webserver directories. Something like: `sudo ln -s /path/to/repo/testing /var/www/mapgame`
1. [Get another server running on your Apache install](/freejoe76/-#examples)


# TODO
- [ ] DEV: Write instructions on how to use testing environment
- [x] MAP: Build blank map
- [ ] MAP: Specify map size
- [ ] MAP: Pass config variables (miles/km, whether to log to server, URL to log against)
- [X] GAME: Get location of dragged map marker
- [X] GAME: Calculate distance (miles/km) from city point
- [ ] MAP: In case we're guessing a country's location, allow using boundary file (KML?) as target location
- [ ] GAME: Calculate distance (miles/km) from country boundary
- [ ] GAME: Make call to remote server to log result
