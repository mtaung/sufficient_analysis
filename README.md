# Sufficient_Analysis, or "How to do statistics with lost data"
A real world example of salvaging lost statistical data, to carry out an ANOVA and independent samples t-test from only sufficient statistics in python.

## Why would you/I need sufficient statistics?
In some cases, as things go in real world projects, data is collected, aggregated, and then unfortunately lost due to unforseen circumstances. In this particular instance, data was collected during a short course on AI. Performance of the AI was to be compared against a benchmark, but due to an unexpected bug the data was lost after training. Given a time constraint to produce a statistical comparison, it was not reasonable to re-train the AI to collect data again. So I was called in to try and salvage the situation as best as possible. 

## What are sufficient statistics?
If you're lucky, you might be able to surrogate your previous data with a synthetic set based on some aggregate information such as your sample means. It's not perfect, and you lose a lot of information this way, but it will at least give you some core results that might still be informative of data that's otherwise lost forever. 

## Using this repository
I recommend just reading the notebooks in the root directory. That's the purpose of setting up this repository at all, on my part. 

## Closing

I hope you never have to use anything like this, but maybe it'll help. 
