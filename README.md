# spectra-examples


## Installation 

Install Conda: https://anaconda.org/anaconda/conda

### Python dependencies 
```
conda env create -f environment.yml
conda init 
conda activate spectra
```

### Install EProver

```
git clone https://github.com/eprover/eprover
cd eprover
./configure --enable-ho
make rebuild
```

Run the examples in the `examples.ipynb.`