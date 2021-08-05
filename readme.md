# NNLS by Lawson & Hanson (1974)

Uses numpy calls as opposed to old fortran binary linked from numpy and scipy.
Binds to MKL, when installed.

# TNT-NN by Myre et al. (2017)

Python version of their code available at https://github.com/ProfMyre/tnt-nn

A fast NNLS method described in "TNT-NN: A Fast Active Set Method for Solving Large Non-Negative Least Squares Problems". Internally, the supplied source code uses an implementation of TNT, a fast least-squares method described in "TNT: A Solver for Large Dense Least-Squares Problems that Takes Conjugate Gradient from Bad in Theory, to Good in Practice".

If you use this software as supplied please cite the above papers. The bibtex to do so is supplied below:

@article{myre2017tnt,
title={TNT-NN: A Fast Active Set Method for Solving Large Non-Negative Least Squares Problems},
author={Myre, Joseph M and Frahm, E and Lilja, David J and Saar, Martin O},
journal={Procedia Computer Science},
volume={108},
pages={755--764},
year={2017},
publisher={Elsevier}
}

@inproceedings{myre2018tnt,
title={TNT: A Solver for Large Dense Least-Squares Problems that Takes Conjugate Gradient from Bad in Theory, to Good in Practice},
author={Myre, Joseph M and Frahm, Erich and Lilja, David J and Saar, Martin O},
booktitle={2018 IEEE International Parallel and Distributed Processing Symposium Workshops (IPDPSW)},
pages={987--995},
year={2018},
organization={IEEE}
}