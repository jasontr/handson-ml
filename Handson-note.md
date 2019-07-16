### 2.3 Get the data
step 1
```
export $ML_PATH="$HOME/ml"
mkdir -p $ML_PATH

pip3 install --user --upgrade virtualenv

cd $ML_PATH
# create virtual environment named env
virtualenv env

# to activate env
source $ML_PATH/env/bin/activate

# install necessary packages
pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn

# to check installation, try to import every modules
python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"

# open jupyter notebook
jupyter notebook
```

step 2
`Housing.ipynb`

