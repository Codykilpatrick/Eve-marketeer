## Market manipulation in the MMORPG Eve Online

![Command line print of what modules to buy](https://i.imgur.com/q2vu8Ux.png)

## Background information 🚀
Eve Online is a Massive Multiplayer Online Role Playing Game. Players are set in the far future and tasked with piloting spaceships to make money (ISK) and do whatever they desire. Players are able to come together to form corporations, then corporations of like minded players form alliances. Eve online has a completely player driver market, that means everything is created and destroyed within the game with very few external injections.

## Problem description 👨‍💻
Our goal with this project was to create a program that would tell us where to buy an item and where to ship it to maximize profits.


## Technologies used 💾
- Jupyter Notebook
- Python
- Git

## Attributions 👥
- CCP games
- everef.net

## Ice box 🧊
- [ ] Automate the pull of daily data
- [ ] Tweak formula as needed
- [ ] Make additional attempts to coduct data analysis on
- [ ] Automate the data reports for each attempt

## Aditional instructions
- Currently the API for Eve's daily market history is down until further notice so we are stuck using the data from 30OCT22-03NOV22.
- I have submitted a trouble ticket with the respone "We are not sure when the API will be back up.
- The program still works the formula is just slightly skewed due to using old historic data.

- For the volume data download the 5 most recent days from: https://data.everef.net/market-history/2022/
- After doing that you must update the "volumes" list in stationpulls.py with the new CSV files.

# Success to date
## Trip one
- Total cost: 176,057,888
- Total profit: 124,000,000

Lessons learned:
- Need to make larger orders, shipping alone accounted for ~33% of our cost.
- Removed certain item groups due to the time taken for sale.
