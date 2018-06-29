# Awesome list for polyhedra recovery:  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome papers about polyhedra recovery.

[research]: https://cdn4.iconfinder.com/data/icons/48-bubbles/48/12.File-32.png "Research"
[slides]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/x-office-presentation-32.png "Slides"
[video]: https://cdn2.iconfinder.com/data/icons/snipicons/500/video-32.png "Video"
[web]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/internet-web-browser-32.png "Website or blog post"
[code]: https://cdn2.iconfinder.com/data/icons/snipicons/500/application-code-32.png "Code"
[other]: https://cdn3.iconfinder.com/data/icons/tango-icon-library/48/emblem-symbolic-link-32.png "Uncategorized"
[awesome]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg "Awesome list"

## Recovery based on support function measurements

Support function estimation means the reconstruction of convex body from the set of its support function measurements. Main works here are:

|Type|Title|Comment|
|---|:---|:---|
|![][research]|[_Prince J.L., Willsky A.S._ Reconstructing convex sets from support line measurements // IEEE Transactions on Pattern Analysis and Machine Intelligence. Apr. 1990. 12(4). P. 377-389](https://dspace.mit.edu/bitstream/handle/1721.1/3016/P-17?sequence=1)|2D reconstruction problem for uniformly distributed angles|
|![][research]|[_Prince J.L._ Geometric model-based estimation from projections. Doctoral dissertation, Massachusetts Institute of Technology, 1988.](https://dspace.mit.edu/bitstream/handle/1721.1/14667/18315465-MIT.pdf?sequence=2)|Prince's PhD thesis with included theory from above Prince&Willsky 1990 paper.|
|![][research]|[_Lele A.S., Kulkarni S.R., Willsky A.S._ Convex-polygon estimation from support-line measurements and applications to target reconstruction from laser-radar data // JOSA A. 1992 Oct 1;9(10):1693-714.](http://www.princeton.edu/~kulkarni/Papers/Journals/j005_1992_lkw_osa.pdf)|The generalization of (Prince & Willsky 1990) to non-uniform distribution of angles|
|![][research]|[_Karl W.C., Kulkarni S.R., Verghese G.C., Willsky A.S._ Local tests for consistency of support hyperplane data // Journal of Mathematical Imaging and Vision. 1996 Jun 1;6(2-3):249-67.](https://dspace.mit.edu/bitstream/handle/1721.1/3331/P-2201-29490295.pdf?sequence=1)|3D problem, constraints consistency criterion. No testing on real data.|
|![][research]|[_Fisher N.I. , Hall P., Turlach B.A., Watson G.S._ On the estimation of a convex set from noisy data on its support function // Journal of the American Statistical Association. 1997 Mar 1;92(437):84-91.](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.1997.10473605)|Convex set estimation based on periodic smoothing methods.|
|![][research]|[_Hall P., Turlach B.A._ On the estimation of a convex set with corners // IEEE Transactions on Pattern Analysis and Machine Intelligence. 1999 Mar;21(3):225-34.](https://ieeexplore.ieee.org/abstract/document/754588/)|Statistical detection of polygon corners based on support function measurements.|
|![][research]|[_Gregor J., Rannou F.R._ Three‐dimensional support function estimation and application for projection magnetic resonance imaging // International journal of imaging systems and technology. 2002 Jan 1;12(1):43-50.](https://doi.org/10.1002/ima.10007)|3D real data testing of (Karl 1996).|
|![][research]|[_Gregor J., Rannou F._ Least-squares framework for projection MRI reconstruction // In Medical Imaging 2001: Image Processing 2001 Jul 3 (Vol. 4322, pp. 888-899). International Society for Optics and Photonics.](https://doi.org/10.1117/12.431168)|?_not investigated in detail_; details of above paper?|
|![][research]|[_Gardner R.J., Kiderlen M., Milanfar P._ Convergence of algorithms for reconstructing convex bodies and directional measures // The Annals of Statistics. 2006 Jun 1:1331-74.](https://projecteuclid.org/download/pdfview_1/euclid.aos/1152540751)|First paper about speed of convergence of the estimation algorithm.|
|![][research]|[_Gardner R.J., Kiderlen M._ A new algorithm for 3D reconstruction from support functions // IEEE transactions on pattern analysis and machine intelligence. 2009 Mar;31(3):556-62.](https://pdfs.semanticscholar.org/d2e4/76a632ec55d0b1a7484a5482122e4e047063.pdf)|Another, more efficient way to solve consistency problem in 3D|
|![][research]|[_Guntuboyina A._ Optimal rates of convergence for convex set estimation from support functions // The Annals of Statistics. 2012;40(1):385-411.](https://projecteuclid.org/download/pdfview_1/euclid.aos/1334581747)|Optimal rates, related to (Gardner et al 2006).|
|![][research]|[_Cai T., Guntuboyina A., Wei Y._ Adaptive estimation of planar convex sets // arXiv preprint arXiv:1508.03744. 2015 Aug.](https://arxiv.org/abs/1508.03744)|Older, draft preprint version of the below paper.|
|![][research]|[_Cai T.T., Guntuboyina A., Wei Y._ Adaptive estimation of planar convex sets // The Annals of Statistics. 2018;46(3):1018-49.](https://projecteuclid.org/euclid.aos/1525313074)|Estimate that has optimal rate in point-wise and body-wise sense.|

## Probing

Some related works that research probing of convex bodies.

|Type|Title|Comment|
|---|:---|:---|
|![][research]|[_Cole R., Yap C.K._ Shape from probing // Journal of Algorithms. 1987 Mar 1;8(1):19-38.](https://www.sciencedirect.com/science/article/pii/0196677487900253)|?_not investigated in detail_; there is also a 1983 technical report with the same title.|
|![][research]|[_Greschak J.P._ Reconstructing convex sets. Doctoral dissertation, Massachusetts Institute of Technology), 1985.](https://dspace.mit.edu/bitstream/handle/1721.1/15285/13620037-MIT.pdf?sequence=2)|Contents the idea that probing of support function is equal to probing of boundary in the dual space.|
