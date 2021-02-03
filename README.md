# **CalPriorSNIa**
## Effective calibration prior on the absolute magnitude of Type Ia supernovae

**priorMB.nb** quickly computes the effective calibration prior on the absolute magnitude M_B of Type Ia supernovae that corresponds to a given determination of H_0. 
See Camarena & Marra [arXiv:1906.11814](https://arxiv.org/abs/1906.11814) and [arXiv:2101.08641](https://arxiv.org/abs/2101.08641) for more details.

Have fun,
[David](http://inspirehep.net/author/profile/D.Camarena.1) & [Valerio](http://inspirehep.net/author/profile/V.Marra.1)


### Calibration priors

The latest H_0 determination by SH0ES is (Riess et al. [arXiv:2012.08534](https://arxiv.org/abs/2012.08534)):
`H_0 = 73.2 ± 1.3 km/s/Mpc`

The corresponding calibration priors depend on the supernova dataset that one wants to use for the cosmological analysis:

Supercal dataset ([Scolnic et al 2015](https://arxiv.org/abs/1508.05361)) ==>
`M_B = -19.2421 ± 0.0375 mag`

Pantheon dataset ([Scolnic et al 2018](https://arxiv.org/abs/1710.00845)) ==>
`M_B = -19.2435 ± 0.0373 mag`

DES-SN3YR dataset ([Brout et al 2018](https://arxiv.org/abs/1811.02377)) ==>
`M_B = -19.2389 ± 0.0336 mag`

### Statistical analysis

When performing cosmological inference, instead of using the prior on H_0:

<a href="https://www.codecogs.com/eqnedit.php?latex=\chi^2_{H_0}&space;=&space;\frac{\big&space;(H_0-H^{\rm&space;SH0ES}_0&space;\big)^2}{\sigma_{H_0}^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\chi^2_{H_0}&space;=&space;\frac{\big&space;(H_0-H^{\rm&space;SH0ES}_0&space;\big)^2}{\sigma_{H_0}^2}" title="\chi^2_{H_0} = \frac{\big (H_0-H^{\rm SH0ES}_0 \big)^2}{\sigma_{H_0}^2}" /></a>,

use the prior on M_B:

<a href="https://www.codecogs.com/eqnedit.php?latex=\chi^2_{M_B}&space;=&space;\frac{\big&space;(M_B-M_B^{\rm&space;SH0ES}&space;\big&space;)^2}{\sigma_{M_B}^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\chi^2_{M_B}&space;=&space;\frac{\big&space;(M_B-M_B^{\rm&space;SH0ES}&space;\big&space;)^2}{\sigma_{M_B}^2}" title="\chi^2_{M_B} = \frac{\big (M_B-M_B^{\rm SH0ES} \big )^2}{\sigma_{M_B}^2}" /></a>.

The prior on the supernova absolute magnitude M_B is to be preferred to the prior on H_0 for the following three reasons:<br/>
i) one avoids potential double counting of low-redshift supernovae,<br/>
ii) one avoids cosmography, in particular fixing the deceleration parameter to the standard model value of q_0=-0.55 ([arXiv:2012.08534](https://arxiv.org/abs/2012.08534)),<br/>
iii) one includes in the analysis the fact that M_B is constrained by local calibration, an information which would otherwise be neglected in the analysis.



### Credits

You can use CalPriorSNIa, or part of it, freely, provided that in your publications you acknowledge its use and cite the papers Camarena & Marra [arXiv:1906.11814](https://arxiv.org/abs/1906.11814) and [arXiv:2101.08641](https://arxiv.org/abs/2101.08641).
If using the provided supernova data, please cite the corresponding paper.