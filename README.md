# Recurrent Deep Sets: Predicting Weekly Gasoline Demand from Traffic Congestion

**Abstract:** I adapt and extend the Deep Sets architecture introduced by Zaheer et al. (2017) to
learn embeddings for set-structured elements in a high-frequency time-series on
their way to predicting the next time-step of a low-frequency series. This is
particularly relevant in economics, where macro-level data is often reported on a
weekly or monthly basis, while micro-level signals take place over irregular and
more frequent intervals. Leveraging a dataset of 33 million traffic congestion events
across 49 states over a six-year period, I attempt to predict the following week’s
data print of motor gasoline product supplied from the current week’s traffic and
weather activity. I show that recurrent Deep Sets outperform conventional
recurrent autoencoder methods, with the final model specification achieving test
predictions within 0.44 standard deviations of observed values.

**Data Sources:** 

Moosavi, S., Samavatian, M. H., Nandi, A., Parthasarathy, S., & Ramnath, R. (2019, July). Short and long-term pattern discovery over large-scale geo-spatiotemporal data. In *Proceedings of the 25th ACM SIGKDD international conference on knowledge discovery & data mining* (pp. 2905-2913).

U.S. Energy Information Administration (n.d.). *Weekly Petroleum Status Report. https://www.eia.gov/petroleum/supply/weekly*
