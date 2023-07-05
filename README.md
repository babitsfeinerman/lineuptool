# lineuptool
Generates a list of players in descending order sorted by fantasy points

This tool scrapes the HTML data from the numberFire projection website, cleans up the data, and returns the player name, position, and fantasy points sorted in descending order. The tool works for the default 'main' slate but is a work in progress for the all-day slate. The players we are searching for are hard-coded in a player names list because they don't change often, and it was very complicated to scrape the roster from Fantrax, so hard-coding was way more manageable. We are running into issues when we try to use Chromedriver and selenium to change the slate and return all the players, not just the ones on the main slate. 
