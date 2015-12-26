Wbridge5
========
This is the convention card used by [Wbridge5][wbr5], a prominent French bridge
software.

The software evaluates hands with real-time double-dummy analysis, unsuitable
to describe in the convention card.  Nevertheless, there is big data from
[Thomas's Bridge Fantasia][thomas] telling us what to bid.

[wbr5]: http://wbridge5.com/
[thomas]: http://bridge.thomasoandrews.com/valuations/

Estimated tricks
----------------
### NT ###
A = 4, K = 2.8, Q = 1.8, J = 1, 10 = 0.4  
Estimated tricks = (Combined points - 7) / 2

### Suit ###
A = 4.5, K = 3, Q = 1.5, J = 0.75, 10 = 0.25  
\- = 3, x = 2, xx = 1  
Estimated tricks = (Combined points + 3) / 3

### Binky points ###
Binky points are directly estimated tricks, either in NT or the best suit
contract.  This is the best additive trick estimator, without knowledge of fit.

Adjustment
----------
### At IMPs ###
Half of the time, the combined hands can make the estimated tricks or more.  
Bidding a grand slam needs 13.5 tricks, i.e. 0.5 more.  
Bidding a game needs 0.5 less tricks.

### Rounding ###
The resolution of evaluation is 0.5 tricks, so one can upgrade the hand by 0.25
tricks to find slightly more games.

Levels
------
### One-level opening ###
Opening at IMPs requires 4.00 NT tricks (12.0 points) or 4.50 suit tricks (12.0 points).  
Opening at MPs requires 4.25 NT tricks (12.5 points) or 4.75 suit tricks (12.75 points).

### Game ###
3NT requires 8.0 tricks (23.0 points) seen at IMPs, 8.5 tricks (24.0 points) at MPs.  
4M requires 9.0 tricks (24.0 points) seen at IMPs, 9.5 tricks (25.5 points) at MPs.  
5m requires 10.0 tricks (27.0 points) seen at IMPs, 10.5 tricks (28.5 points) at MPs.

### Slam ###
Small slam requires 12.0 tricks seen, i.e. 30.0 points for 6x, 31 points for 6NT.  
Grand slam requires 13.5 tricks seen, i.e. 34.5 points for 7x, 34 points for 7NT.
