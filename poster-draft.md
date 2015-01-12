1. using unsupervised learning methods on hyperspectral images taken on Mars. (CRISM)
2. take 10 spots from equatorial region where i expect the insolation is the most uniform to give stronger reflectance signals from the ground
3. each spot has around 6 different spectral processed version. 

vnir_rgb
Enhanced visible color
red = 592nm
green = 533 nm
blue = 492nm

ir_ira
IR surface brightness
gray level = brightness at 1330nm

vnir_fem
Oxidized iron minerals
red = BD530 (ferric minerals)
green = SH600 nm (coatings)
blue = BDI1000nm (variety of iron minerals)

ir_maf
Mafic mineralogy
red = OLINDEX (olivine or iron phyllosilicates)
green = LCPINDEX (low-Ca pyroxene)
blue= HCPINDEX (high-Ca pyroxene)

ir_phy
Hydroxylated silicates
red = BD2300 (Fe/Mg phyllosilicate)
green = BD2210 (Al phyllosilicate or hydrated glass)
blue=BD1900 (hydrated sulfates, clays, glass, or water ice)

ir_hyd
Bound water
red = SINDEX (water-containing minerals or water ice)
green = BD2100 (monohydrated sulfates or water ice)
blue = BD1900nm. (hydrated sulfates, clays, glass, or water ice)

ir_ice
Water and CO2 ice
red = BD1900 (water ice or hydrated sulfates, clays, or glass) 
green = BD1500 (water ice) 
blue=BD1435 (CO2 ice)




4. run through density estimation, clustering (e.g., k-means), hidden Markov models, principal component analysis.
5. and analyse the discovered knowledge. 
6. 

