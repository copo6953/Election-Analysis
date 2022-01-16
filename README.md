# Colorado Congressional District Election-Analysis
## Election Audit Overview:
* Assisting the Colorado Board of Elections with an election audit of a Congressional district using python. The goal was to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the election winner based on the popular vote.
### Election-Audit Results:
* 369,711 total votes were cast in the election.
* 10.5% of those votes (38,855) were cast in Jefferson County.
* 82.8% (306,055) were cast in Denver County.
* 6.7% (24,801) were cas in Arapahoe County.
* Denver County had the highest voter turnout with 306,055 votes cast.
* Charles Casper Stockham recieved 23.0% of the vote (85,213).
* Diana DeGette recieved 73.8% of the vote (272,892).
* Raymon Anthony Doane recieved 3.1% of the vote (11,606).
* Diana DeGette won the election with 272,892 votes, 73.8% of all votes cast.
![Election_Results](https://github.com/copo6953/Election-Analysis/blob/main/Images/Election_Results.png)
#### Election-Audit Summary:
* The python code I used for this election-audit can be modified for any election the Colorado Board of Elections would like to use it for, even for a presidential election. The code would need to be modified to read and calculate state statistics in combination with county statistics. This could be accomplished fairly easily by creating a list to store state names and a dictionary to store the votes tied to those states just like I did for the counties in this election. Another for loop would need to be included in the code to iterate through each state and make the necessary calculations. I believe this code would make the Colorado's Board of Elections audit process much more efficient!
![County_List](https://github.com/copo6953/Election-Analysis/blob/main/Images/County_List.png)
