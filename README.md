[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Text-Fabric function(ality) replacement demo

This small repository contains the following two notebooks:

- [Function(ality) replacement exploration](FunctionReplacementDemo.ipynb): this demonstrates briefly various options available in Python to replace functions. It describes some pro and cons of each methods and provides reasoning on why a specific method is used (by me) in our TF dataset.

- [API instance bound replacement and additions demo](test_two_TF_datasets.ipynb): This demo clearly shows that replacing a Text-Fabric API method (like search and show in MPTF) or adding a new method (like viewtype in N1904) is strictly limited to the specific dataset it is applied to.

The purpose of this repository is to provide insight on the power and flexability of the (optional) file [app.py](https://github.com/CenterBLC/N1904/blob/main/app/app.py) that can be added to an Text-Fabric dataset. It can also function as a kind of quick start to implement this on your own Text-Fabric dataset.

# About Text-Fabric

The Text-Fabric framework is designed to facilitate the analysis and manipulation of large-scale textual data, particularly in the context of ancient languages and biblical texts. The engine of Text-Fabric is its powerful Python library, which provides a comprehensive set of tools for processing and querying structured text data efficiently. The software package is accessible at [https://github.com/annotation/text-fabric](https://github.com/annotation/text-fabric).
