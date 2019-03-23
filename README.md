# consistency fv and hal

This is the repository of the published paper
"Consistency between Luesher's finite volume method
and HAL QCD method for two-baryon systems in lattice QCD",
JHEP03(2019)007, DOI:10.1007/JHEP03(2019)007
[arXiv:1812.08539 [hep-lat]](https://arxiv.org/abs/1812.08539).

In this paper, we discuss the consistency between
the Luescher's finite volume method and HAL QCD method.

* notes

  + Eigenvalues and eigenfunctions.ipynb

  summarize eigenvalues and plot eigenfunctions

  + Projected effective energy  shifts.ipynb

  calculate the eigenmode projected effective energy shift

  + R-corr. decomposition.ipynb

  evaluate the overlap coefficients

  + Reconstruction of the effective energy shift.ipynb

  plot reconstructed effective energy shifts (Run "R-corr. decomposition.ipynb" before using this note)


  + (Test) R-corr. to potential and eigenfunction.ipynb

  "Test code" for the HAL QCD method and evaluate the eigenvalues
  from the R-correlator

* data

  + eigen

  the eigenvalues and eigenfunctions (See "Eigenvalues and eigenfunctions.ipynb")

  + Rcorr

  jackknife samples of the Rcorr (See "Example R-corr. to potential and eigenfunction.ipynb)

  + dEeff_xixi_1s0.pkl

  the effective energy shift (XiXi(1S0))
