# Overview

I present notebooks with temperature sliceplots, 2D Histograms, and spectra for seven different rays. Any file with the keyword, '(Reduced)' uses three rays as opposed to seven. Ray 1, Ray 2, and Ray 3 in these notebooks are the equivalent to Ray 1, Ray 3, and Ray 4 in the documents containing seven rays. . Ray 1 passes through cool gas (~10<sup>4</sup> K) almost entirely, while Rays 2 and 3 travel through cool, intermediate (~10<sup>5</sup> K), and hot (~10<sup>6</sup> K) gas. I think it is worth studying how different spectra look in the intermediate temperature gas as opposed to the cool gas. Additionally, the reduced notebooks only perform calculations on ions and lines that are commonly or can be easily observed. These exclude Al IV, Fe IV, and Mg III.


## Slice Plots and 2D Hist. for All Gas / Slice Plots and 2D Hist. for All Gas (Reduced)

These notebook show the x, y, and z temperature slice-plots for each ray and illustrates their corresponding 
2D rho-temperature histogram weighted by cell mass.


## Slice Plots and 2D Hist. for Single Ions (Scaled Equally)

This notebook shows the Slice Plots and Rho-Temperature histograms for a single ion. These plots are weighted by ion mass ranging form 10<sup>-11</sup> M<sub>&odot;</sub> to 5*10<sup>5</sup> M<sub>&odot;</sub>.

## Comparing Spectra 140 (Reduced)

This notebook present the simulated spectra of each ray. Each plot has a field of view of 4 &#8491; except for the Ly &alpha;.

## Instrument vs. Manual (Reduced and with Noise) / Instrument vs. Manual (Reduced, Noise, Velocity)

These notebooks illustrate a step plot of each absorption line using d&lambda;'s pertaining to real instruments like the Cosmic Origins Spectrograph (COS) and a plot showing what the spectra looks like theoretically with no noise and a d&lambda; of 0.001.
The d&lambda;'s (in Angstroms per pixel) corresponding to each instrument are as follows:

- COS-G130M: 0.00997


- COS-G160M: 0.01223


- COS-G140L: 0.0803


- COS-G185M: 0.037


- COS-G225M: 0.033


- COS-G285M: 0.4


Source: https://hst-docs.stsci.edu/cosihb/chapter-5-spectroscopy-with-cos/5-1-the-capabilities-of-cos


"Instrument vs. Manual (Reduced, Noise, Velocity)" shows the absorption spectra in velocity space.

## Spectra at Specific Temps/ Spectra at Specific Temps (Combined)

In this notebook, I plot some absorption lines due to the cold gas (< 5x10<sup>4</sup> K), intermediate-temperature gas 
(5x10<sup>4</sup> K < T < 5x10<sup>5</sup> K), and hot gas (> 5x10<sup>5</sup> K) in the given ray. The combined version of this notebook includes these spectra plus an additional plot that defines the cold gas as T < 2x10<sup>4</sup> K, the intermediate-temperature gas as 2x10<sup>4</sup> K < T < 5x10<sup>5</sup> K, and the hot gas as T > 5x10<sup>5</sup> K.


## v vs. y (With Slice)

This notebook shows slice plots weighted by line-of-sight velocity (velocity in the y direction) for rays 2 and 3 and depicts a Line-of-sight Velocity vs. y Position scatterplot.
