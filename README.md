# avert

### How to run
- Install the requirements. 
- The `AVERT` class provides an interface for resilience evaluation. Here's the code sample:
```python
f_cont = <contribution function> # select a contribution measure from avert/model/distance.py
avert = AVERT(f_cont = <contribution function>)
r = avert.eval(testId, metricMetadata, normalInterval, faultyInterval, metrics) # the resilience value
```
- The dataset pkl file is organized by `(testId, metricMetadata, normalInterval, faultyInterval, metrics)`.

