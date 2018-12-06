# AtlasesFUS
Hosting of modified atlases for stereotactic navigation for focused ultrasound research

This repository hosts code and the  modified Nifti 3D mouse and rat atlases based on the **Scalable Brain Atlas**:

https://scalablebrainatlas.incf.org


Each atlas was manually inspected to recenter the 0 at Bregma. The size in mm is important to calibrate the area of the SVG scalable templates.

Consult the **notebook** `Atlases/Tools for Atlas preparation/Convert Atlases for Stereotactic navigation.ipynb` for details for the conversion.

# Citation

When using these atlases in your research, plase be sure of citing the following references

## P56 Allen mouse atlas
* Lein ES, Hawrylycz MJ, Ao N, et al. (2007) "Genome-wide atlas of gene expression in the adult mouse brain." Nature 445(7124):168-76. [doi 10.1038/nature05453]

* Rembrandt Bakker, Paul Tiesinga, Rolf Kötter (2015)
"The Scalable Brain Atlas: instant web-based access to public brain atlases and related content."
Neuroinformatics. http://link.springer.com/content/pdf/10.1007/s12021-014-9258-x (author copy: arXiv:1312.6310)


## Walxhom rat atlas
* Papp EA, Leergaard TB, Calabrese E, Johnson GA, Bjaalie JG (2014) "Waxholm Space atlas of the Sprague Dawley rat brain" NeuroImage 97:374-386. [doi 10.1016/j.neuroimage.2014.04.001]

* Kjonigsen LJ, Lillehaug S, Bjaalie JG, Witter MP, Leergaard TB (2015) "Waxholm Space atlas of the rat brain hippocampal region: Three-dimensional delineations based on magnetic resonance and diffusion tensor imaging." NeuroImage 108:441–449. [doi 10.1016/j.neuroimage.2014.12.080]

* Sergejeva M, Papp EA, Bakker R, Gaudnek MA, Okamura-Oho Y, Boline J, Bjaalie JG, Hess A (2015) "Anatomical landmarks for registration of experimental image data to volumetric rodent brain atlasing templates." Journal of Neuroscience Methods 240:161-169. [doi 10.1016/j.jneumeth.2014.11.005]

* Rembrandt Bakker, Paul Tiesinga, Rolf Kötter (2015)
"The Scalable Brain Atlas: instant web-based access to public brain atlases and related content."
Neuroinformatics. http://link.springer.com/content/pdf/10.1007/s12021-014-9258-x (author copy: arXiv:1312.6310)

## VSNetal11 rat atlas
* Valdés-Hernández PA, Sumiyoshi A, Nonaka H, Haga R, Aubert-Vásquez E, Ogawa T, Iturria-Medina Y, Riera JJ, Kawashima R (2011) "An in vivo MRI template set for morphometry, tissue segmentation, and fMRI localization in rats" Front Neuroinform 5(26). [doi 10.3389/fninf.2011.00026]

* Rembrandt Bakker, Paul Tiesinga, Rolf Kötter (2015)
"The Scalable Brain Atlas: instant web-based access to public brain atlases and related content."
Neuroinformatics. http://link.springer.com/content/pdf/10.1007/s12021-014-9258-x (author copy: arXiv:1312.6310)

# Licensing

The code provided in the  notebook `Atlases/Tools for Atlas preparation/Convert Atlases for Stereotactic navigation.ipynb` is distributed under the 3-clause BSD license, see notebook for license. **This license does not extend to the atlas data itself (read above)**

The `svgscale` `Atlases/Tools for Atlas preparation/svgscale` script is provided under the [GNU General Public License v3.0](https://github.com/numixproject/numix-tools/blob/master/LICENSE)

The Walxhom rat atlas (according to [Scalable Brain Atlas](https://scalablebrainatlas.incf.org)) is distributed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/)
