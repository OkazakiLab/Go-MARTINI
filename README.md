# Go-MARTINI

The modified script to construct a Go-MARTINI system. 

It uses a new cutoff scheme to define native contacts of proteins [Mahmood, Poma and Okazaki, Submitted].

## Installation
First, clone or download the repository,
```
git clone https://github.com/OkazakiLab/Go-MARTINI.git
cd Go-MARTINI/
```
## Usage
```
python2.7 go_martinize_MPO.py -f 3hah_dimer1-CA.pdb -o 3hah_dimer1-CA.top -x 3hah_dimer1-CA-GoCG.pdb -dssp /usr/bin/dssp -p backbone -ff elnedyn22 -go -goepsilon 6.276
```
