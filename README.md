# RCV

Election simulations comparing ranked choice voting (RCV) with the current electoral system (CES) in the U.S.

This repo contains files to compute and visualize winners and extremism levels of a ranked-choice voting system and of the current election system (first-past-the-post, primary system).

```general_distributions.py``` uses a generic distribution (randomly generated via cubic splines) or a specified well-known distribution of voters to calculate the winners and extremism levels.

```uniform_distributions.py``` uses a uniform distribution of voters.

```standard_election.py``` uses a given number of randomly generated voters.

These files are used for the simulations in the paper titled "Ranked Choice Voting, the Primaries System, and Political Extremism: Theory and Simulations," by Avidit Acharya, Rohan Cherivirala, Robin Truax and Karsen Wahal, all of Stanford University.
