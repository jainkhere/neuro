Connect to chimera13

```
srun --pty --ntasks=2 -p DGXA100 --mem=256G -w chimera13 -t 2-24 /bin/bash
```

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

