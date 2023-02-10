# [ M i s p l a c e d ]  O p t i m i s m

Trading Simulator.  Stay Greedy.

## Objective
The main objective of the project is to help myself learn and demonstrate the implementation of API's, web app front-ends, database usage and ultimately, automated test frameworks.
Once the web-api-db architecture is in place, it will serve as a context for implementing a variety of automated test frameworks.
I set myself a 1-year target to have a working appliation, API and automated test framework.

## Pilot 
- Pilot has a range of attributes:
    - Name
    - Location
    - Status (ACTIVE or DEAD)
    - Credits
    - Buildings (that are owned)
    - Moth(s) (and any installed Cargo Pods)
    - Faction Association (Friend, Enemy or Neutral to each of the Factions)


## Pilot Registration
- Enter a Pilot name
- Choose a Crater as a starting location (e.g. Alpha, Downtown, HighRise, Mines, etc...)
- Choose a Role (Trader, Scavenger, Aggressor)
- Starting credits: 10000


## Trading Posts
- Each trading post has it's own Needs List, accessible from any other trading post **within the same crater**.
- Sales List can be accessed from any trading post, indicating where both Cheapest and Nearest goods are available.


## Gameplay
- Depending on Crater selection, the Pilot starts at the corresponding trading post.
- Trade is motivated by checking the Needs List of other trading posts, and the Sales List to purchase and trade goods with the trading post.
- As a Pilot flies from one location to another, random events can happen during the flight that affect:
    - Moth damage (Shield, Engine, Hull, Electronics etc..)
    - Goods picked up during random salvage

## Flight Factors
- Depending on what goods the Pilot is carrying as cargo, can affect how much attention they attract, and therefore how much damage they receive.
- Depending how far they travel, increases the attention and random events that can occur.


## Repairs
- Repairs can be carried out at select repair shops (Breaker Makers etc.)
- They must be travelled to in order for repairs to be made.

## Energy and Lightwells
- Initially, this will be ignored, as it is complex to implement when to stop at lightwells and what the consequences of this are.


