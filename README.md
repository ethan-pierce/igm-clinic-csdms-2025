# IGM clinic, CSDMS 2025
### *"Accelerating Glacier and Surface Processes Modeling with Machine Learning and New Python Libraries"*

Irina Overeem<sup>1</sup>, Ethan Pierce<sup>2</sup>, Billy Armstrong<sup>3</sup>, and Jocelyn Reahl<sup>1</sup>
<sub>
1. University of Colorado Boulder
2. Dartmouth College
3. Appalachian State University
</sub>

contact: irina.overeem@colorado.edu

Running ice dynamics models is difficult. Running ice dynamics models over geomorphic time scales is even more difficult! In this clinic, we show how the Instructed Glacier Model ([IGM](https://github.com/jouvetg/igm/tree/main/igm/modules))<sup>a</sup> can accelerate your models of glaciated landscapes.

a. Jouvet, G., & Cordonnier, G. (2023). Ice-flow model emulator based on physics-informed deep learning. Journal of Glaciology, 69(278), 1941-1955.

[jhub-link]: https://explore.openearthscape.org/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fethan-pierce%2Figm-clinic-csdms-2025&urlpath=lab%2Ftree%2Figm-clinic-csdms-2025%2F%3Fautodecode&branch=main
[badge]: https://img.shields.io/badge/Run%20on-EarthscapeHub-orange

[![Run on EarthscapeHub][badge]][jhub-link]

If you're intending to run IGM on the OpenEarthScape JupyterHub, first run the following command in a Terminal window (on the Hub):
```
source activate igm
```
It is recommended to navigate to the examples directories before running IGM, e.g.
```
cd examples/mendenhall
```
Then, you can run IGM with:
```
igm_run --param_file params.json
```
If you ever want to run an example again, just be sure to delete the ```output.nc``` file first:
```
rm output.nc
```

Enjoy!
