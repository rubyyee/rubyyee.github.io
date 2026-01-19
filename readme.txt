Text for the Projects page:
- Dye tracer experiments at Tufts Cove
		To gain insight about water mass transport, mixing, and dilution in Halifax Harbour, several dye tracer releases were performed using fluorescent Rhodamine dye released from an outfall pipe at Tufts Cove. Using measurements obtained from underway profiling with sensors that measure fluorescence, we can construct transects of dye concentration to understand how properties like stratification and tide phase affect the spatial distribution of the dye. The motivation for this work is related to ocean alkalinity enhancement: alkalinity releases are currently being conducted by the company Planetary Technologies at Tufts Cove for the purpose of carbon dioxide removal. Unlike alkalinity, the dye is easy to measure in-situ using fluorometers, so we can make inferences about how alkalinity concentrations evolve---important for assessing environmental impact, and efficiency of carbon dioxide removal---based on the dilution rates measured using the dye. 
		These experiments were conducted through collaboration across multiple research groups and industry partners, including the CERC.Ocean group (https://www.dal.ca/diff/cerc.html), the Marine Environmental Monitoring Group (https://memg.ocean.dal.ca/index.html), the Musgrave group, and Planetary Technologies(https://www.planetarytech.com/). 
	- static/images: map.png; dye_drone.jpg; aug_oct_transects.png

- Numerical model of the Halifax Harbour estuary
		Using the General Estuarine Transport Model (GETM) (link: https://getm.eu/), I worked with colleagues at the Leibniz Institute for Baltic Sea Research to develop a realistic local model for Halifax Harbour and Bedford Basin. This model was initialized and validated against the observational measurements obtained during our monthly surveys and during the dye release experiments, and forced at the boundaries using output from the Marine Environmental Monitoring Group (https://memg.ocean.dal.ca/index.html)'s larger-domain ROMS model. In GETM, we can simulate passive tracer release from Tufts Cove. Using modelling data, we are able to perform analyses that are not possible at the spatial and temporal resolution of the observations from the dye experiments (e.g., calculating the total amount of tracer in the domain and estimating detectable surface areas over several weeks).
	- static/images: surf_animation_for_presentation.mp4

- Idealized model of lateral dilution for Ocean Alkalinity Enhancement (OAE)
		Due to the nonlinear relationship between total alkalinity (TA) and pCO_2,  an increase in TA when TA is already high will yield a minimal decrease in pCO_2, while an increase in TA when TA starts low will yield a much larger decrease in pCO_2. As a result, the rate of carbon dioxide removal (CDR) will differ depending on the dilution of a plume. For a fixed addition of alkalinity, a more laterally-dilute plume will flux faster than a less laterally-diluted plume. I am working on a series of idealized 2D MATLAB models to illustrate this phenomenon. The big open question here is, "under what circumstances does the nonlinear TA-pCO_2 relationship matter for CDR?"

- Turbulence observations in the Arctic Ocean from temperature microstructure
	 During a 2018 research cruise in the Arctic Ocean's Canada Basin, measurements of very small-scale temperature were obtained using a fast-sampling instrument (Rockland's MicroRider-1000) attached to a lowered CTD rosette. Using these measurements, I estimated turbulent parameters like the dissipation rate of temperature variance, and the turbulent diffusivity of temperature. A large part of this project was also focused on fine-tuning rejection criteria for these kinds of microscale temperature observations. 
	 
	 We were able to quantify heat fluxes between different water masses in the Arctic Ocean at the study site. The key results of this work were: 
		- Average turbulent temperature diffusivity is elevated by 1–2 orders of magnitude on the shelf compared to over the deep slope
		- A similar magnitude (O(1 Wm^{-2})) of heat is fluxed into the cold halocline from the Atlantic Water below as from the overlying surface layer
		- Heat fluxes as high as 50 Wm 2 are occasionally observed in the surface layer
		Read the published article here. (https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023JC019932)

- Monthly transects in Halifax Harbour/Bedford Basin
	  Our group has been conducting monthly transect surveys in Bedford Basin and Halifax Harbour since 2021. This is a very dynamic estuary: the temperature-salinity structure can change dramatically between months due to sporadic intrusions of dense water from outside of the estuary, and large seasonal temperature changes on the order of ∆T~30degC are possible, and salinity can vary by tens of g/kg depending on recent freshwater discharge.
	- static/images: TS.gif, 2024-01_transect.png, surveying1.jpeg, surveying2.jpg




Wishlist:

Projects page
- figures appear in one column, text beside (like the about page)
- projects listed on main page are clicakble, and link to each project in the projects page
- figure captions below each figure
In general:
- banner image is the same width as text
- footer text doesn't get scrunched up when the width of the page changes (could put each part on a separate line
- banner image caption in footer only appears on main page
- email/download CV/git linnkedin etc. on first page is always centred