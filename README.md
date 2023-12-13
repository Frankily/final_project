# recommendGAT

recommendGAT is a graph attention transformer model designed to create a personalized recommendation system for web-scale large graphs 

## Setup:

### Clone recommendGAT git repo:
```bash
git clone https://github.com/Frankily/final_project.git
```

### Environment setup:

If you do not have Anaconda installed, follow these [instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

To verify installation,  
```bash
conda list
```

To install environment,
```bash
conda install --file requirements.txt
```

To activate,  
```bash
conda activate plzz
```

### Usage:

Due to file sizes, first generate the user item interactions graph and the item item interactions graph with the Data Preprocessing portion. BE wary of the size of graphs. Also, one must attain the metadata about the items by parsing the metadata file that is able to be downloaded online on https://jmcauley.ucsd.edu/data/amazon/ and https://www.yelp.com/dataset.

To reproduce the results from the GAT model and the user embedding generation, follow the instructions in `final_model.ipynb`.
