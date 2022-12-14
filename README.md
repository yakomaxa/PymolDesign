# PymolDesign: Protein sequence design on PyMOL

Design your protein for given backbone structure on PyMOL!


# What's this? PymolDesign = ColabDesign + PymolFold

Run protein MPNN and predict the structure by ESM API on PyMOL.

Sequence design part was adapted from [ProteinMPNN@ColabDesign](https://github.com/sokrypton/ColabDesign/tree/main/mpnn) by [@sokrypton](https://github.com/sokrypton) and his collaborators.

Structure prediction part was adapted from [PymolFold](https://github.com/JinyuanSun/PymolFold) by [@JinyuanSun](https://github.com/JinyuanSun)

# Dependency

* colabdesign
* matplotlib (required by colabdesign)
* requests

Install them via pip bundled with your PyMOL. Be careful not to destroy your (purchased) PyMOL.

**Installation of colabdesign**

```pip -q install git+https://github.com/sokrypton/ColabDesign.git@v1.1.0```

# Usage

From PyMOL console,

```run design.py```

Then

```design selection, name```

For example,

``` load mybackbone.pdb ```

``` design mybackbone, myfirstdesign```

will yield the designed model templated by your backbone and named myfirstdesign.

# Note 

This is a repository under development. Issues and PR would be welcomed.

# References

Add reference for ColabDesign and proteinMPNN here

```bibtex
@article{lin2022language,
  title={Language models of protein sequences at the scale of evolution enable accurate structure prediction},
  author={Lin, Zeming and Akin, Halil and Rao, Roshan and Hie, Brian and Zhu, Zhongkai and Lu, Wenting and dos Santos Costa, Allan and Fazel-Zarandi, Maryam and Sercu, Tom and Candido, Sal and others},
  journal={bioRxiv},
  year={2022},
  publisher={Cold Spring Harbor Laboratory}
}
```

