# 2022-08-01-uproot-awkward-columnar-hats

Tutorials for Uproot Awkward Columnar HATS, a hands-on tutorial hosted by the [Fermilab LPC](https://lpc.fnal.gov) on August 1, 2022 from 10:30 to 1:00 U.S. Central.

See the [event page for videoconferencing details](https://indico.cern.ch/event/1186603/).

## How to participate

Run the JupyterLab code with us, altering examples and asking "what if" questions along the way.

The preferred way to run these notebooks is through a public cloud service called Binder:

<p align="center">
  <a href="https://mybinder.org/v2/gh/nickmanganelli-sr/2022-08-01-uproot-awkward-columnar-hats/v1.4">
    <img src="https://mybinder.org/badge_logo.svg" alt="Launch Binder" height="40">
  </a>
</p>

Navigate in the JupyterLab file view (left sidebar) to the desired lesson. Note that Binder has limited save functionalityy (reloading your web browser will take you to a new instance, nominally), and it may take up to a minute to start up.

## Running everything on your own computer

This course will not cover installation of the software, but everything can be installed with pip or conda, standard mechanisms for installing Python packages. See [requirements.txt](requirements.txt) for a list of pip package names.

## Running everything on SWAN

The notebooks here are largely compatible with the LCG_102 (swan) stack, which can be started from [swan.cern.ch](https://swan.cern.ch). An old version of numba prevents the last cell of the awkward demo from working, showing numba-jitted functions running on awkward+vector.

## Browsing the material online

The cells of the JupyterLab notebooks are deliberately unevaluated—we will discover their output during the tutorial. However, if you're coming here after the event and want to look up how we did something, see the [evaluated2021](evaluated2021) directory for evaluated versions of the three notebooks from the 2021 LPC HATS, and eventually [evaluated](evaluated) for the 2022 HATS notebooks.

## Uprooting hats that are awkwardly columnar

<p align="center"><img src="img/blog1841_TheBuriedGnome800.jpg" width="400"></p>

[(Used with permission.)](https://bagelhot.blogspot.com/2007/02/web-daze.html)
