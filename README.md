# mglcmdtools

## 1 Introduction

`mglcmdtools` is a collection of common cmd tools intended to be used in Python3 scripts. By Guanliang MENG, see https://github.com/linzhi2013/mglcmdtools. 


## 2 Installation

    pip install mglcmdtools


## 3 Usage
    
    from mglcmdtools import rm_and_mkdir, runcmd, longStrings_not_match_shortStrings


    rm_and_mkdir('Newdirectory')

    rm_and_mkdir('Newdirectory', force=True)


    cmd = 'ls -lhtr /'
    runcmd(cmd)

    runcmd(cmd, verbose=True)


    Long_strings = ['AABB', 'CCDD', 'EEFF']
    Short_strings = ['AA', 'EE']
    longStrings_not_match_shortStrings(Long_strings, Short_strings)
    # ['CCDD']


## 4 Author
Guanliang MENG

## 5 Citation
Currently I have no plan to publish `mglcmdtools`.







