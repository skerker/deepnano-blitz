# Ultra fast ONT basecaller

This is a very fast basecaseller which can basecall reads as fast as they come
from MinION.

## Limitations

* Works only on 64bit linux.
* On AMD cpus it is advised to use: `export MKL_DEBUG_CPU_TYPE=5`
* You need python3 (tested with python 3.6)

## Instalation

* Install Rust (you should already have it ;) )
* Ask for nightly version `rustup default nightly-2019-12-11`
* Clone this repository
* Run `python setup.py`
* Change Rust version to whatever you like

## Running

`deepnano2_caller.py --output out.fasta --directory reads_directory/`
