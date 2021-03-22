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
The file `Pantheon_and_M.param` contains a naive example on how to use this prior along with the Pantheon likelihood. To update/change the prior on M just edit the file `absolute_M/absolute_M.data`. This current version corresponds to `M_B = -19.2435 ± 0.0373 mag` and should be only used with Pantheon supernovae. 
