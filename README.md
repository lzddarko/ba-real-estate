# BA Real Estate

**An analysis of the real estate market in Bosnia and Herzegovina, using a snapshot of OLX.ba listings**


## The data
The data was pulled from [OLX.ba](https://olx.ba/nekretnine) and preprocessed, removing unneeded parameters and anonymizing it (by removing listing titles, images, exact location, etc).  
It was then stored in the `data/` directory, which is shared here.  
It has been split by real estate type, each JSON file containing entries in the following format: 
```JSON
{
    "city": "Sarajevo",
    "rooms": "5+",
    "area_m2": 150.5,
    "price_eur": 150000,
    "listed_by": "shop",
    "condition": "used"
}
```

## The analysis

The analysis was done using Python data analysis and visualization packages, such as **scikit-learn** and **seaborn**, and the notebooks can be found in the `notebooks/` directory.  

## Modifications and interaction
You can open `.ipynb` files locally in an editor that supports Jupyter notebooks, such as Visual Studio Code with Jupyter extension installed.  
To modify and run them you should have Python 3 and necessary packages installed.  
Packages required are `pandas`, `scikit-learn`, `xgboost`, `seaborn`, `matplotlib`.
