# Ballotpedia_Webscrape

This is a webscrape script written in Python that scrapes all the social media accounts of all public officials in every state in the United states. The script essentially makes three different data frames. 

1) The first dataframe, the "People" Dataframe pulls all of the public officials and thier ballotpedia pages.
2) The second dataframe, the "Socials" Dataframe pulls all of the social media accounts featured on each public officials ballotpedia page.
3) The third dataframe, the "Meta" Dataframe pulls all the meta data for each public official including thier positions, name, party and data assumed office.

The final dataframe compiles the above three dataframe into a single dataframe in which each row is one public official, thier metadata and a list of their social media accounts. 
