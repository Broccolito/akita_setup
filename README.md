# Set up AKITA
```bash
git clone https://github.com/calico/basenji.git
cd basenji
conda env create -f prespecified.yml
conda activate basenji
conda install tensorflow==2.28
python setup.py develop --no-deps
```

