# Historical OCT denoising archive

This repository is not the active SABIDS-Net benchmark runtime. The maintained
seven-method implementation lives in the sibling SABIDS-Net repository under
`tools/oct_denoise_benchmark/`.

The directories currently present here were collected from multiple upstream
projects. A preliminary audit found explicit license files only in
`DenoiSegOCT-main`, `OCT_DDPM-main`, and parts of
`OCT-denoising-package-main`. Absence from this short list is not a license
conclusion; it means redistribution permission has not yet been verified.
Therefore third-party source, papers, binaries, model weights, datasets and
generated results are intentionally not staged by the current migration.

Before publishing any archived implementation:

1. identify its exact upstream URL and revision;
2. record its license and retain attribution/notice files;
3. remove bundled papers, data, outputs, weights and binaries;
4. prefer an upstream submodule when redistribution and repository stability
   permit it;
5. keep this repository private when permission is unclear.

BM3D in the active benchmark is installed as the pinned `bm3d==4.0.3`
dependency; its source or binaries are not copied from this archive.
