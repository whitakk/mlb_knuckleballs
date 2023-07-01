# mlb_knuckleballs
analysis of knuckleball pitchers in ML
### How to use 

1. Set up conda environment
- create environment from .yml file: `conda env create -f environment.yml`
- additonally install `pybaseball` package into that environment: `pip install pybaseball`
    - (couldn't get pipenv to play nicely with juypter on the PC I used for this + wasn't worth untangling for this quick project)

2. (optional, if you want to refresh list of knuckleballers): run notebooks in `notebooks/helpers/*` in order 
    - otherwise the default list is already saved in `data/input`

3. run `notebooks/knuckleball_trend.ipynb` notebook and view result