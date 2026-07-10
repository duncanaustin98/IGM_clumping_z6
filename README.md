
# Data Release: IGM Clumping Factor Measurements at z ≈ 6
 
**Companion data release to:** [Austin et al. 2026a, "Resolving the ionizing photon budget crisis with JWST/NIRCam HII clumping constraints at z=6"]
 
---
 
## Catalogue: `Austin+26a.fits`
 
One row per galaxy. Available in FITS format.
 
| Column | Units | Description |
|---|---|---|
| `UNIQUE_ID` | — | Globally unique source identifier |
| `SURVEY_ID` | — | Unique source identifier in each survey |
| `SURVEY_NAME` | — | Survey name |
| `RA`, `Dec` | deg (J2000) | SExtractor source coordinates |
| `z_eazy` | - | Redshift from eazy (zbest) |
| `z_pipes` | - | Redshift from bagpipes (median) |
| `MUV` | AB mag | Intrinsic UV magnitude measured directly from photometric fluxes entirely within [1250,3000]Angstrom |
| `beta` | - | Rest-frame UV slope measured directly from photometric fluxes entirely within [1250,3000]Angstrom |
| `xi_ion` | dex(Hz/erg) | Ionizing photon production efficiency from bagpipes, extended source corrected |
| `Ndot_ion` | dex(Hz) | Ionizing photon production rate from bagpipes, extended source corrected |
| `Av` | AB mag | Calzetti+00 V-band dust attenuation from bagpipes |
| `Mstar` | dex(Msolar) | Stellar mass from bagpipes, extended source corrected |
| `SFR_10/100` | dex(Msolar/yr) | SFR from bagpipes averaged over 10/100 Myr, extended source corrected |
| `sSFR_10/100` | dex(1/yr) | sSFR from bagpipes averaged over 10/100 Myr, extended source corrected |
| `star_forming` | — | Within the star forming subsample |
| `smouldering` | — | Within the smouldering subsample |
| `ext_src_UV` | — | UV extended source correction, clipped between [1, 10] |
| `ext_src_F444W` | — | F444W extended source correction, clipped between [1, 10] |
| `is_mass_complete` | — | Within the 90% stellar mass complete sample |
| `final_sample` | — | Galaxy candidate not excluded as brown dwarf, spurious, or diffraction spike |
| `brown_dwarf` | — | Within the brown dwarf subsample |
| `spurious` | — | Is a spurious object |
| `LRD` | — | Within the LRD subsample |
| `diffraction_spike` | — | Has been removed as a diffraction spike |

---
 
## Citation
 
If you use this dataset, please cite:
 
```bibtex
@ARTICLE{Austin2025,
       author = {{Austin}, Duncan and {Harvey}, Thomas and {Conselice}, Christopher J. and {Adams}, Nathan J. and {Rusakov}, Vadim and {Li}, Qiong and {Westcott}, Lewi and {Goolsby}, Caio and {Madgwick}, Kai and {Arcidiacono}, James and {Ricotti}, Massimo and {Newman}, Sophie L. and {Seeyave}, Louise T.~C. and {Trussler}, James and {Frye}, Brenda and {Grogin}, Norman A. and {Jansen}, Rolf A. and {Koekemoer}, Anton M. and {Pirzkal}, Nor and {Rutkowski}, Michael and {Windhorst}, Rogier A.},
        title = "{Resolving the ionizing photon budget crisis with JWST/NIRCam HII clumping constraints at z=6}",
      journal = {arXiv e-prints},
     keywords = {Astrophysics of Galaxies, Cosmology and Nongalactic Astrophysics},
         year = 2025,
        month = dec,
          eid = {arXiv:2512.10839},
        pages = {arXiv:2512.10839},
          doi = {10.48550/arXiv.2512.10839},
archivePrefix = {arXiv},
       eprint = {2512.10839},
 primaryClass = {astro-ph.GA},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2025arXiv251210839A},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```
and, where applicable, the dataset DOI: [10.17909/9k10-pb47].
Please also consider citing EPOCHS-DR2 for the data (Austin et al. in prep)
 
---
