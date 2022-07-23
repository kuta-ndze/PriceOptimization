<h2 align="center"> <b>Price Optimization</b> </h2>

AIM

- Provided with Restaurant Cafe data , we are able to leverage price elasticity with historical Cafe sales data to measure customers' responsiveness towards quantity demanded or supply due to price changes and find the optimal price to set for their items for maximum profit i.e striking a balance in low or high price for optimal profit.

METHODOLOGY

- <b> Exploratory data analysis </b>

  - Any covariate with like SchoolBreak, Weekends that increases sales and has no effects on price are dropped since we are not interested in seeing effects on sales due to these covariates.
  - Check for missing values.
  - Uncovering multiple facets of merge data.

- <b> Modelling </b>

  - Price elasticity of demand (PED) measure use to show the responsiveness of the quantity demanded of a good or services to changes in price when nothing else is change i.e relationship between demand and price. i.e the effective desire for something changes as price changes. It gives the % change in quantity for 1 % increase in price
    Mathematically The formula for the price elasticity (ǫ)

        $$
         \begin{align}
         e = \frac{\%\Delta Q}{\%\Delta P}
         \end{align}
        $$

  - We will look at sales of Cafe that sales burgers, the Cafe owner wants to know the optimal price to set for their item in order to gain maximum profit. Note. If the prices are high, the sales will reduce and if the prices are low the sales will increase and hence total profit will decrease. So the task here is to get a sweet spot that will give us the maximum profit. So we are trying to find a linear relationship between quantity and price hence use a linear regression in this case
