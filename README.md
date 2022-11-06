# PymolDesign: Protein sequence design on PyMOL

Design your protein for given backbone structure on PyMOL

# What's this?

Run protein MPNN on PyMOL and predict the structure by ESM API.

Design part was adapted from [ProteinMPNN@ColabDesign](https://github.com/sokrypton/ColabDesign/tree/main/mpnn) by [@sokrypton](https://github.com/sokrypton) and his collaborators.

Structure prediction part was adapted from [PymolFold](https://github.com/JinyuanSun/PymolFold) by [@JinyuanSun](https://github.com/JinyuanSun)

# Dependency

* colabdesign
* matplotlib (required by colabdesign)
* requests

Install them via pip bundled with your PyMOL. Be careful not to destroy your (purchased) PyMOL.

Installation of colabdesign

```pip -q install git+https://github.com/sokrypton/ColabDesign.git@v1.1.0```

# Note 

This is a repository under development. Issues and PR would be welcomed.
