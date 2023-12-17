# Network-Science-Data-Modelling

### Use case:

Soccer Team Recruiter: Use graph data to target best suited players for a club at a specific position in terms of player versatility, work rate and availability

### Benefit:

As a Soccer Team Recruiter, you want to be fully capable of analyzing player viability in a team based setting. This could mean assuring that a player has a certain rating or that a player practices and performs with a specific work rate. As a recruiter you may want to find a player who closely resembles a retiring player or player with an expiring contract with respect to rating and similar traits. Also, as a recruiter you are looking for the next big star who does not possess a high rating at the time of recruiting.

Team player recruiters can use this data model to gain greater insight into player traits, ratings and group classifications. This data graph model will help with player recruiting through visualization of data statistics relevant to age, contract expiries, player ratings and work rate. Additionally, this graph model can be used to display commonality of traits amongst players of various rating groups.

This data model can be referred to as a talent pool of players where all players are filtered into rating groups, non dependent of the positions they play. Having such a data model allows soccer team recruiters to make comparisons between players of similar rating groups. These comparisons can include commonality of traits and rankings based on which players share the most traits with other players. Trait comparisons can easily be made due to the implementation of the :SHARES_TRAIT relationship, which is encoded with the name of the specific trait shared.

### Data Graph Model Questions:

Which club produces the highest value players?
Who are the youngest high rating players soon to become free agents and what are their positions/ preferred positions?
Who is the oldest high rating player for a particular club with a contract that will soon expire?
Who is the oldest high rating player for a particular position with a contract that will soon expire?
What is the work rate classification of a particular player with a soon to expire contract on a given team?
Which players within the same Rating Group are most similar?
Rating Group is either High (player ratings >= 85 ), Medium(84 >= player ratings >= 61 ) or Low (player ratings <= 60) 


### Languages/Tools used:

. Python
. Jupyter Notebook
. Neo4j

