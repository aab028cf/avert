# avert

### How to run
First install the requirements. 

The `AVERT` class provides an interface for resilience evaluation. Here's the code sample:

```python
avert = AVERT()
r = avert.eval(testId, metricMetadata, normalInterval, faultyInterval, metrics) # the resilience value
```

The dataset pkl file is organized by `(testId, metricMetadata, normalInterval, faultyInterval, metrics)`.

