# Estimating the effect of speed limits policies in London
## MSc summer project
### Difficulty: **medium/high difficulty** :grimacing: :grimacing: or :grimacing: :grimacing: :grimacing:, depending on specs

**Description**: Schemes across the UK and Europe to reduce speed limits in the name of safety have become increasingly popular in recent years, with the primary goal of lowering the number of crashes, casualties and speeding seen on the roads. The evidence on the effectiveness of the policy is not entirely clear, with some studies indicating that at traffic speeds of 30-40mph, the risk of pedestrian death as a result of a collision with a vehicle is 5.5 times more likely than at speeds between 20-30mph, while others (specifically, a three-year research project by Queen’s University Belfast) claiming that 20mph speed limits across the city have made little difference to safety, but did reduce the volumes of traffic (see [here](https://jech.bmj.com/lookup/doi/10.1136/jech-2022-219729), for example).

The objective of this project is to use a Bayesian [Interrupted Time Series](https://en.wikipedia.org/wiki/Interrupted_time_series) modelling to investigate the impact of the introduction of the 20mph speed limit in much of the UK on the number of road accidents. The `R` package [`stats19`](https://cran.r-project.org/web/packages/stats19/index.html) is a good way of downloading, processing and analysing the UK road collision data; this dataset will be used as the basis of the modelling.

More advanced versions of the modelling/project will include a spatial dimension (for example using geo-tagged data from [official sources](https://roadtraffic.dft.gov.uk/downloads)) to determine the effects of the policy.

The project requires good knowledge of programming in `R`, understanding of Bayesian hierarchical modelling. More specific tools/skills include:

- fitting Bayesian models using [Integrated Nested Laplace Approximation] (https://gianluca.statistica.it/talks/intro-inla/INLA_NASH.pdf)
- Poisson regression for count data
- Spatial/spatio-temporal models (see [here](https://gianluca.statistica.it/slides/armitage/seminar/) for example).
