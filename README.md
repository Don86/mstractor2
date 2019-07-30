# MStractor (Another Version)

Not really another version; just a re-typed version so that I can understand what's happening, line-by-line.

### Repo structure
* `/data`, containing *all* `.mzXML` files, plus a `metadata.csv` describing which samples belongs to which group.
* An `ipynb` of code

### `ipynb` Contents

1. Input Params
2. Check out a Reference.
3. Start Processing all Files:
    3a. Find Chrom Peaks
    3b. Peak Grouping
    3c. RT Alignment
4. Annotation with CAMERA
5. Descriptive Statistics

All other files/directories in the repo are created in the process of running the script. 
