# Notes

# Steps
- Download and install anaconda using this link
- Create a conda env using 
```commandline
conda create -n haystack_search
conda activate haystack-search
```

- Clone the haystack 
```commandline
git clone https://github.com/deepset-ai/haystack.git
cd haystack
pip install --upgrade pip
pip install -e .
```

- Install numba using
```commandline
pip install numba
```

- Start the docker daemon
- Run tutorials
```commandline
python haystack/tutorials/Tutorial1_Basic_QA_Pipeline.py
```