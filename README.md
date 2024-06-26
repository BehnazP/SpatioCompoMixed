## Human land-use and land-cover maps based on pollen observations and Anthropogenic land-cover changes for Europe
### The usage of the land-cover maps is free, however attribution to the publication is required.

The `.csv` files in Human land-use and Land cover Maps folder
1. Human-land-use_land-cover-maps_all_1900CE,
2. Human-land-use_land-cover-maps_elevation_1900CE,
3. Human-land-use_land-cover-maps_all_1725CE,
4. Human-land-use_land-cover-maps_elevation_1725CE,
5. Human-land-use_land-cover-maps_all_1425CE,
6. Human-land-use_land-cover-maps_elevation_1425CE,
7. Human-land-use_land-cover-maps_all_1000BCE,
8. Human-land-use_land-cover-maps_elevation_1000BCE,
9. Human-land-use_land-cover-maps_all_4000BCE,
10. Human-land-use_land-cover-maps_elevation_4000BCE,

based on the results in Pirzamanbein and Lindström (2022) (https://doi.org/10.1002/env.2743).

The columns represent
* Lon: longitude
* Lat: latitude
Land Cover Changes (LCC)
* LCC_*_C: Coniferous forest
* LCC_*_B: Broadleaved forest
* LCC_*_U: Unforested land
Natural Land Cover (NLC)
* NLC_*_C: Coniferous forest
* NLC_*_B: Broadleaved forest
* NLC_*_O: open land
Human Land Use (HLU)
* HLU: Human land-use

These results obtained by running the Demo.m function in the src folder in MATLAB.
Demo.m sets the structures, dependency and the names. It calls Main.m function to run the MCMC sampling. The results of the Main.m functions are based on the papers mentioned above. However, some of the functions can be used in general cases, dealing with Gaussian Markov Random fields, Compositional Data, Dirichlet and Beta distribution.

### Reference:
* Pirzamanbein, Behnaz and Johan Lindström. "Reconstruction of past human land use from pollen data and anthropogenic land cover changes." Environmetrics 33, no. 6 (2022): e2743. (https://doi.org/10.1002/env.2743)
* Pirzamanbein, Behnaz, Anneli Poska, and Johan Lindström. "Bayesian Reconstruction of Past Land Cover From Pollen Data: Model Robustness and Sensitivity to Auxiliary Variables." Earth and Space Science 7, no. 1 (2020): e2018EA00057. (https://doi.org/10.1029/2018EA000547)
* Pirzamanbein, Behnaz, and Johan Lindström. "Reconstruction of Past Human land-use from Pollen Data and Anthropogenic land-cover Changes Scenarios." arXiv preprint arXiv:1910.10993 (2019). (https://arxiv.org/abs/1910.10993)
* Pirzamanbein, Behnaz, Johan Lindström, Anneli Poska, and Marie-José Gaillard. "Modelling Spatial Compositional Data: Reconstructions of past land cover and uncertainties." Spatial statistics 24 (2018): 14-31. (https://doi.org/10.1016/j.spasta.2018.03.005)

### Licenses
#### Code
MATLAB code for combing the spatial compositional data with proportional data, specifically for reconstructions of past land cover and human land use.
Copyright (C) 2020  Pirzamanbein Pirzamanbein

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
#### Data
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Land-cover maps based on pollen observations for Europe</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Behnaz Pirzamanbein</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/BehnazP/SpatioCompoMixed" rel="dct:source">https://github.com/BehnazP/SpatioCompoMixed</a>.
