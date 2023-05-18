A quick attempt at calculating the fraction of grid pixels that intersects with some land geometry.

### Installation

Using conda or one of its leaner offspring, create a Python environment:

```
micromamba create -f ./environment.yml
```

### Execution

Activate the environment and start a notebook server:

```
micromamba activate pixel-fractions
jupyter notebook pixel_land_fraction.ipynb
```

### To-do

Improve performance! This method will be slow for any reasonable size grid...
