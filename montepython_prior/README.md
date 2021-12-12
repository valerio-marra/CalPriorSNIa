# Prior on the absolute magnitude of Pantheon Type Ia supernovae

### Files

   - `Pantheon_and_M.param`
   - `absolute_M/__init__.py`
   - `absolute_M/absolute_M.data`

### Description
To use the prior on the absolute magnitude of Pantheon supernovae with your montepython installation you should paste `absolute_M` into the `likelihoods` folder doing:
```
cp -r absolute_M /path-to-your-montepython/montepython/likelihoods/

```
The file `Pantheon_and_M.param` contains a naive example on how to use this prior along with the Pantheon likelihood. To update/change the prior on M just edit the file `absolute_M/absolute_M.data`. The current version uses `M_B = -19.2478 ± 0.0294 mag`, which corresponds to the latest H_0 determination by SH0ES of `H_0 = 73.04 ± 1.04 km/s/Mpc` (Riess et al. [arXiv:2112.04510](https://arxiv.org/abs/2112.04510)). It should only be used with Pantheon supernovae. 

### Credits
If using this likelihood please cite the papers Camarena & Marra [arXiv:1906.11814](https://arxiv.org/abs/1906.11814) and [arXiv:2101.08641](https://arxiv.org/abs/2101.08641).
