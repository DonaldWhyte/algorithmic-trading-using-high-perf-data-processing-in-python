# High Performance Data Processing in Python V2.0

### [View Presentation Slides](http://donaldwhyte.github.io/high-performance-data-processing-in-python-v2)

Talk demonstrating how to massively optimise data processing and numerical computation in Python. We build an automated US stock trading strategy using stock pricing data for 7000 stocks. We take running historical simulations of this strategy from one month to less than an hour.

Topics covered:

* motivations for fast numerical processing in Python
* why Python is a slow programming language
* fast numerical processing in `numpy`
* vectorisation
* using `numba` to optimise non-vectorised code

## Running Presentation

You can also run the presentation on a local web server. Clone this repository and run the presentation like so:

```
npm install
grunt serve
```

The presentation can now be accessed on `localhost:8080`. Note that this web application is configured to bind to hostname `0.0.0.0`, which means that once the Grunt server is running, it will be accessible from external hosts as well (using the current host's public IP address).
