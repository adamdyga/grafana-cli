# grafana-cli
Commandline Interface to Grafana with predictive query caching support

The goal of this project is to use a command line interface and some query intelligence to support monitoring with low prometheus server resources.
Instead of replicating PromQL to the servers, the command line agent uses local caches and predictive logic to get the metrics out. 

In case the server cannot respond with metrices, the CLI interpolates the response and fills gaps.

Work in progress.
