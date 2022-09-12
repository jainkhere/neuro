Install miniconda, then install the RISTER environment:

```
conda env create -f RISTER.yml

conda activate RISTER
```

Then run the convert.py script:

```
cd Neuroglancer
mkdir OUTPUTFOLDER
./convert.py ORIGINALFOLDER OUTPUTFOLDER
```
