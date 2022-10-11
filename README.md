# About

This repository contains code related to the following paper on measurements of self-interference at 28 GHz using phased arrays.

[1] I. P. Roberts, A. Chopra, T. Novlan, S. Vishwanath, and J. G. Andrews, "Beamformed Self-Interference Measurements at 28 GHz: Spatial Insights and Angular Spread," _IEEE Trans. Wireless Commun._, Jun. 2022, (early access).

Using the code in this repo, which is based on measurements and statistical characterizations in [1], users can:
 - draw realizations of mmWave self-interference levels (INR values) in full-duplex mmWave systems;
 - conduct statistical analyses of full-duplex mmWave communication systems;
 - develop methods to mitigate self-interference in full-duplex mmWave communication systems;
 - evaluate solutions for full-duplex mmWave communication systems.

This work is based on nearly 6.5 million measurements of self-interference taken at 28 GHz in an anechoic chamber using two colocated 256-element phased arrays mounted on separate sides of an equilateral platform. Please see [1] for details.

If you use this code or our paper in your work, please cite [1] with the following BibTeX.

```
@ARTICLE{roberts_beamformed_si_measurements_2022,
    author={I. P. Roberts and A. Chopra and T. Novlan and S. Vishwanath and J. G. Andrews},
    journal={IEEE Trans.~Wireless~Commun.},
    title={Beamformed Self-Interference Measurements at 28 {GHz}: Spatial Insights and Angular Spread}, 
    year=2022,
    month=jun,
    note={(early access)}
}
```

Related work can be found at https://ianproberts.com.

# Contents

This repo contains the following MATLAB code:
 - a main script illustrating example usage
 - five `get` functions, which return statistical parameters based on some inputs
 - five `.mat` files that contain the tabulated fitted parameters in [1]
