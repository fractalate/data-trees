# Trees of Chicago Data Analysis and Visualization

* [Exploration of the Dataset](./explore_chicago_il.ipynb) (Notebook).

## Data

The USDA Forest Service data is public domain and is included in this repository, however some data like the World Checklist of Vascular Plants (WCVP) is not able to be integrated here. You'll have to download this data yourself in order to run the various notebooks.

You can find the WCVP dataset on the [WCVP file server](http://sftp.kew.org/pub/data-repositories/WCVP/). Please download `wcvp_dwca.zip` (I used version 14). Put it in `data/wcvp_dwca` and unzip it.

## Python Libraries

* `jupyter`
* `matplotlib`
* `scipy`
* `pyproj`

## Citations

[U.S. Department of Agriculture Forest Service Urban DataMart](https://research.fs.usda.gov/products/dataandtools/urban-datamart)

* [Chicago, IL Dataset](./data/Urban%20DataMart/Chicago_IL_CSV/) (Directory)
  - Downloadable at [https://research.fs.usda.gov/products/dataandtools/urban-datamart](https://research.fs.usda.gov/products/dataandtools/urban-datamart).
* [Urban Forest Inventory and Analysis Database User Guide](./documents/Urban%20DataMart/wo-v10-0_nov2024_ug_urbanfiadb_database_description.pdf) (PDF)
  - Provides detailed information about the tables and columns in the dataset.
  - Downloadable at [https://research.fs.usda.gov/understory/urban-forest-inventory-and-analysis-database-user-guide](https://research.fs.usda.gov/understory/urban-forest-inventory-and-analysis-database-user-guide).

WCVP (2025). "Govaerts R (ed.). 2025. WCVP: World Checklist of Vascular Plants. Facilitated by the Royal Botanic Gardens, Kew. [WWW document] URL http://sftp.kew.org/pub/data-repositories/WCVP/ [accessed 28 May 2025]."
