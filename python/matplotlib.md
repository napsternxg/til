---
layout: default
title: Python Plotting
parent: Python
permalink: /python/plotting
---

# Fix legend in matplotlib after making the plot

Sources: 
* https://stackoverflow.com/questions/35200094/change-size-alpha-of-markers-in-the-legend-box-of-matplotlib/35200637
* https://stackoverflow.com/questions/48694620/how-to-set-legend-marker-size-and-alpha


```python
# plot has lines with markers
for lh in plt.gca().get_legend().legendHandles:
  lh.set_alpha(1)  # Fixes line alpha
  lh._legmarker.set_markersize(10) # Fixes line marker size
  lh._legmarker.set_alpha(1) # Fixes line marker alpha
```
