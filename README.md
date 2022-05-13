# Transients-in-HETDEX
Classification of transient sources observed during the Hobby-Eberly Telescope Dark Energy Experiment (HETDEX)

File: hetdex_sources_final_table.txt
Columns:
1: ZTF name
2: R.A. (J2000)
3: Dec. (J2000)
4: mjd_start_ztf
5: mjd_stop_ztf
6: mjd_hetdex 
7: alerce_type (VS, AGN, SN, asteroid, bogus)
8: alerce_probability
9: spectral type (Harvard classes for stars, Hubble-classes for galaxies)
10: signal-to-noise
11: chi^2 
12: redshift (0 for stars, >0 for galaxies) 
13: classification (star, galaxy, agn, low, uncertain) 

File: hetdex_sources_real_final_table.txt
(the same as above, but for real (!= bogus) ALeRCE sources
