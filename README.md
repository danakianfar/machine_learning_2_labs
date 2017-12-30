# Machine Learning 2

[![License](http://img.shields.io/:license-mit-blue.svg)](LICENSE)

## Description

Code for the labs of the [Machine Learning 2](http://coursecatalogue.uva.nl/xmlpages/page/2017-2018-en/search-course/course/34043) course at the University of Amsterdam.

### Lab 1 - Independent Component Analysis (ICA)
- [Assignment and Solutions](src/lab1/lab01_KIANFAR_GALLEGO.ipynb)

Original Signals             |  Reconstructed Signals
:-------------------------:|:-------------------------:
<img src="src/lab1/img/original.png" width="400" />  |  <img src="src/lab1/img/phi3.png" width="400" />

- Reconstructed audios: [Speech](src/lab1/demix/demix1_phi3.wav) - [Beethoven](src/lab1/demix/demix2_phi3.wav) - [Street](src/lab1/demix/demix4_phi3.wav)

### Lab 2 - Sum-Product and Max-Sum Algorithms
- [Assignment and Solutions](src/lab2/lab02_KIANFAR_GALLEGO.ipynb)

<p align="center">
  <img src="src/lab2/bn.png" width="300" /><br />
  <i>Bayesian Network </i>
</p>

### Lab 3 - Expectation Maximization (EM) and Variational Autoencoders (VAE)
- [Assignment and Solutions](src/lab3/lab03_KIANFAR_GALLEGO.ipynb)

<p align="center">
  <img src="src/lab3/img/em.png" width="500" /><br />
  <i>EM on MNIST </i>
  <br />
  <br />
  <img src="src/lab3/img/vae.png" width="500" /><br />
  <i>Learned Manifold of the VAE on MNIST</i>
</p>

## Testing
Refer to each lab and run the iPython notebook as follows.
``` 
jupyter notebook $notebook_name$.ipynb
```

## Dependencies
iPython notebook
- Lab 1: SciPy, NumPy, matplotlib
- Lab 2: itertools, NumPy, matplotlib
- Lab 3: gzip, SciPy, torch, matplotlib

## Contributors

- [Dana Kianfar](https://github.com/danakianfar)
- [Jose Gallego](https://github.com/jgalle29)

## Copyright

Copyright © 2017 Dana Kianfar and Jose Gallego.

<p align="justify">
This project is distributed under the <a href="LICENSE">MIT license</a>. Please review the <a href="http://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html">UvA regulations governing Fraud and Plagiarism</a> in case you are a student at the UvA.
</p>
