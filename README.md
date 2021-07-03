# hw_m5_financial_planners

This file serves as a current and future financial planner for members of a credit union.

First it analyzes their current assets to determine whether they have sufficient assets to serve as an emergency fund (equivalent to at least 3-months-worth of household income). It accomplishes by using Alpaca API calls to retrieve up to date pricing of their crypto and stock/bond holdings. It applies these prices to the number of shares and totals the values to explain whether or not they have enough value in their investments to meet their emergency fund requirements.

It then pulls 10 years of data on the stock/bond portion of the members' portfolio as input values for Monte Carlo simulations for 30 and 10 years out. It creates overlay plots and distribution histograms for each, as well as summary statistics to help members determine (within a 95% confidence interval) whether their current assets are likely to  appreciate enough to allow them to retire in 30 or ten years, respectively.