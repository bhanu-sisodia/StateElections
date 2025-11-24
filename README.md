This repository contains a Python script that uses a Monte Carlo simulation to model the probability distribution of a winning candidate's vote count.
It determines the likelihood of a winning vote count falling into specific vote ranges (bins) when both the Total Votes and the Winning Vote Share are assumed to be uniformly distributed within a defined range.
🎯 Key Insight
The simulation shows (on expected lines) that even if the input variables (Total Votes and Winning Share) are uniformly distributed, the resulting Winning Votes distribution is not uniform.
Instead, it forms a bell-shaped curve—a "pyramid"—where a certain vote count range has a significantly higher probability of occurring than the extreme low or high vote counts.

I use this as an input to do another exercise (using Binomial distribution), the question I was trying to answer: What's the probability that many (say 10) winning candidates will have their votes within 1000 votes range. The question was driven by allegations of a suspected election frausd if a winning party has a lot f candidates winning by similiar total votes or vote margins.
My analysis on this topic can be found at bhanusisodia.com

Feel free to fork this repository, adjust the parameters, and explore on your own.
