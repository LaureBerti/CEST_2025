# Forest Resilience, Precipitation, and Ecosystem Service Value: A Correlation and Trend Analysis

Python source code for reproducing our CEST 2025 paper results. 

This work is supported by the European Horizon Project [eco2adapt]( https://www.eco2adapt.eu/) [grant agreement ID 101059498] (eco2adapt:
Ecosystem-based Adaptation and Changemaking to Shape, Protect and Maintain the Resilience of Tomorrow’s
Forests).












### Authors
* Pius Nwachukwu 
* Laure Berti-Équille

### Abstract

Ecosystem service value (ESV) is critical for understanding ecosystems' economic benefits and their responses to environmental change. This study uses Earth Observation (EO) data, statistics, and machine learning methods to evaluate ESV trends across multiple continents from 2000 to 2024. Three key datasets were used: MODIS NDVI for vegetation monitoring, CHIRPS precipitation data, and the ESVD database. Data preprocessing includes data cleaning, feature engineering, and outlier detection. We compared Random Forest, XGBoost, and ensemble stacking models to predict key variables and their relationships, such as kNDVI, as a proxy of forest resilience and ESV trends, precipitation patterns, and biome-specific variables. Our results show that kNDVI changes across continents reveal various patterns in vegetation dynamics that are in-line with precipitation patterns and are weakly correlated with ESV changes for forest biomes. Our study emphasizes the significance of time interdependence and climate variability in ESV predictive modelling. Future efforts focus on refining the time/space granularity of data collection and aggregation techniques and incorporating more environmental indicators to improve model robustness and application in policy-making. 

### Installation
Clone the repository and navigate into the project directory:

```bash
git clone https://github.com/laureberti/CEST_2025.git 
cd CEST_2005
```
Install and activate the environment
```bash
conda activate cest_2025_env
```
or
```bash
source  cest_2025_env/bin/activate
```

- Download the datasets from https://drive.google.com/drive/folders/1Ape1onmoq5CdOHzkXTy--doM5jCacA9U?usp=sharing
- Install all the required libraries in your environment
- Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip3 install ipykernel eemont wxee earthengine-api geopandas pandas numpy scikit-learn ace-tools matplotlib seaborn setuptools
python3 -m ipykernel install --user
jupyter lab &   
```


## Citation
If you use the code or dataset, please cite our paper preprint with:
```latex
@inproceedings{cest_2025,
      title={Forest Resilience, Precipitation, and Ecosystem Service Value: A Correlation and Trend Analysis}, 
      author={Pius Nwachukwu and Laure Berti-Équille},
      year={2025},
      month={September},
      booktitle={Proceedings of the International Conference on Environmental Science and Technology (CEST)}
}
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contact

* <a href="mailto:laure.berti@ird.fr">Laure Berti-Équille</a>
