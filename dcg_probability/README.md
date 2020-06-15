# Distributions
This package is intended to simplify calculating Gaussian and Binomial distributions and visualize the results of these calculations.
Capable of processing personal inputs or processing from a file import by using the `plot_histogram_pdf()` method which shows a \
histogram of probability density function outputs.

## Import instructions
Use the following commands:

1. In your terminal, type `pip install dcg-probability`

### Gaussian
2. From your python file, import the Guassian class with 

`from dcg_probabilities import Gaussian`

3. Instantiate a Gaussian object and read a txt data file that should have one number (float) per line like so:

`obj = Gaussian()`

`obj.read_data_file(<file_path>)`

If your development environment supports visualizations, using the method `obj.plot_histogram_pdf()` \
will plot a histogram of the probability function outputs for the data

### Binomial
Follow all the same steps for Gaussian, including the arguments for probability and sample size as so:

`obj = Binomial(p=.25, sample_size=70)`
