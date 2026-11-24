# Mycelial_Growth_Analysis_and_Strain_Selection
Mycelial growth rate analysis and strain selection in Phlebopus bruchii

## Experimental design

Mycelial growth was evaluated in three *Phlebopus bruchii* strains (LT8, LT27, and LT130) isolated from basidiomes collected at different locations in the Chaco Serrano forest of Argentina. Each strain was grown under four culture conditions resulting from the combination of two culture media (malt extract agar, MEA, and potato dextrose agar, PDA) and two pH levels (4 and 6). Each strain-treatment combination was tested in eight replicates (Petri dishes).
Plates were inoculated with 7.5-mm mycelial plugs and incubated at 29 ± 1 °C in darkness. Mycelial growth was measured along two perpendicular axes every three days, from day 4 to day 23 after inoculation (seven measurements in total).
The daily mycelial growth rate (mm/day) was calculated for each replicate and measurement interval as the difference between mean colony diameters divided by the elapsed time. The mean growth rate across measurement intervals was then calculated for each experimental unit (Petri dish).

## Statistical analysis

Differences in mean daily mycelial growth rate among strains and culture conditions were evaluated using a generalized linear model (GLM) with a Gamma distribution and identity link. The model included strain, culture treatment (medium × pH), and their interaction as fixed effects.
Model assumptions were assessed using simulated residuals with the `DHARMa` package. Estimated marginal means were obtained using `emmeans`, and pairwise comparisons were performed with Tukey adjustment (α = 0.05). Compact letter displays were used to facilitate the interpretation and graphical representation of significant differences.
