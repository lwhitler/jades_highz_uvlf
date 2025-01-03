# The $z \gtrsim 9$ galaxy UV luminosity function from the JWST Advanced Deep Extragalactic Survey: insights into early galaxy evolution and reionization (Whitler et al. 2025)

This repository contains the full set of postage stamps, SEDs, and the source catalog for the samples underlying [Whitler et al. (2025)](https://arxiv.org/abs/2501.00984). Please see [arXiv:2501.00984](https://arxiv.org/abs/2501.00984) for full details and email lwhitler@arizona.edu if you have any questions.

To read the source catalog:
```
import astropy.table as Table
source_cat = Table.read('whitler2025_highz_uvlf_catalog.fits', format='fits')
```
