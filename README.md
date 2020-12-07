# Go-MARTINI

The modified script to construct a Go-MARTINI system. For the original version, please see http://info.ifpan.edu.pl/~panos/panos/GoMartini.html

It uses a new cutoff scheme to define native contacts of proteins [Mahmood, Poma and Okazaki, Submitted].

## Usage
First, clone or download the repository,
```
git clone https://github.com/OkazakiLab/Go-MARTINI.git
cd Go-MARTINI/
```
Then, it can be executed in the same way as the original version.
```
python2.7 go_martinize_MPO.py -f 3hah_dimer1-CA.pdb -o 3hah_dimer1-CA.top -x 3hah_dimer1-CA-GoCG.pdb -dssp /usr/bin/dssp -p backbone -ff elnedyn22 -go -goepsilon 6.276
```

## Note
The modifications we made to the original script is in the function called "gocontacts" (Line 3281). 
