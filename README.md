# GeoStatsTutorials

[![gitter](https://img.shields.io/badge/chat-on%20gitter-bc0067.svg)](https://gitter.im/JuliaEarth/GeoStats.jl)
[![nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/JuliaEarth/GeoStatsTutorials)

Tutorials in the form of Jupyter notebooks for the [GeoStats.jl](https://github.com/juliohm/GeoStats.jl) framework.

## Notebooks

The notebooks are better viewed on nbviewer:

- [Estimation problems](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/EstimationProblems.ipynb)
- [Variogram modeling](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/VariogramModeling.ipynb)
- [Anisotropic models](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/AnisotropicModels.ipynb)
- [Directional variograms](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/DirectionalVariograms.ipynb)
- [Declustered statistics](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/DeclusteredStatistics.ipynb)
- [Two-point statistics](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/TwoPointStatistics.ipynb)
- [Gaussian processes](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/GaussianProcesses.ipynb)
- [Image quilting](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/ImageQuilting.ipynb)
- [Cookie-cutter](http://nbviewer.jupyter.org/github/juliohm/GeoStatsTutorials/blob/master/notebooks/CookieCutter.ipynb)

They can be run locally with:

```julia
using Pluto

cd("notebooks")

Pluto.run()
```

## Contributing

Contributions are very welcome, please submit a pull request or open an issue with an example that you feel is missing.
