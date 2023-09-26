# APMASK PROJECT

#### Gustav Karlsson, Linus Lindell, Markus Norling

#### Intro:
In this project, you will work through the whole process of solving a real-world problem using
probabilistic machine learning. You are tasked to estimate the skill of players involved in a competition
based on the results of matches between pairs of players. You will first define a probabilistic model,
where all the quantities are represented as random variables, based on the Trueskill Bayesian ranking
system developed by Microsoft research for raking on-line matches. The model assigns a skill to each
player, in the form of a Gaussian random variable. When two players meet in a match, the outcome
of that match is a Gaussian random variable with a mean equal to the difference between the two
players’ skills. The result of the match is 1 (indicating the victory of Player 1) if the outcome is
greater than zero, -1 if it is less than zero (indicating the victory of Player 2).
You will use Bayesian inference to find the posterior distribution of the players’ skills given obser-
vations of the results of matches. Because the posterior distribution is intractable, you will use two
different approximation methods based on graphical models.
On the course website, you will find the SerieA.csv dataset containing the results of the Italian
2018/2019 Serie A elite football (soccer) division; however, the Trueskill model can be used to solve
a variety of skill and ranking problems. Later in the project, you will be asked to use a dataset of
games/competitions of your choosing. We suggest that you start thinking about it early on
