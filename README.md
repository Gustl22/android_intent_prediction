### Setup

Download the traces from [RICO data sets](http://interactionmining.org/rico#quick-downloads) and copy it to `sources/datasets/RICO/`:
```
.
├── rnn
└── sources
    └── datasets
        └── RICO
          ├── traces
          │   └── filtered_traces
          │       └── [some.app.com]
          │           └── trace_1
          │            ├── screenshots
          │            └── view_hierarchies
          └── unique_uis
              └── combined
```

### Python Virtual environment

To checkout the virtual environment of python, call:
```shell
source $HOME/.venv/bin/activate # or any other path to venv
```

To include system packages check out [this stackoverflow post](https://stackoverflow.com/a/55600285/5164462).

# Tensorflow with CUDA / GPU

Install Tensorflow with Nvidia GPU support
https://stackoverflow.com/a/76836703/5164462
