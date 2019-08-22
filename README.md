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

Support function estimation means the reconstruction of convex body from the set of its support function measurements.

### Least squares estimator for support function values

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Prince J.L., Willsky A.S._ Reconstructing convex sets from support line measurements // [IEEE Transactions on Pattern Analysis and Machine Intelligence. Apr. 1990. 12(4). P. 377-389](https://dspace.mit.edu/bitstream/handle/1721.1/3016/P-17?sequence=1)|2D reconstruction problem for uniformly distributed angles|
|![][research]|_Prince J.L._ Geometric model-based estimation from projections. [Doctoral dissertation, Massachusetts Institute of Technology, 1988.](https://dspace.mit.edu/bitstream/handle/1721.1/14667/18315465-MIT.pdf?sequence=2)|Prince's PhD thesis with included theory from above [[Prince & Willsky 1990](https://dspace.mit.edu/bitstream/handle/1721.1/3016/P-17?sequence=1)].|
|![][research]|_Lele A.S., Kulkarni S.R., Willsky A.S._ Convex-polygon estimation from support-line measurements and applications to target reconstruction from laser-radar data // [JOSA A. 1992 Oct 1;9(10):1693-714.](http://www.princeton.edu/~kulkarni/Papers/Journals/j005_1992_lkw_osa.pdf)|The generalization of [[Prince & Willsky 1990](https://dspace.mit.edu/bitstream/handle/1721.1/3016/P-17?sequence=1)] to non-uniform distribution of angles|
|![][research]|_Karl W.C., Kulkarni S.R., Verghese G.C., Willsky A.S._ Local tests for consistency of support hyperplane data // [Journal of Mathematical Imaging and Vision. 1996 Jun 1;6(2-3):249-67.](https://dspace.mit.edu/bitstream/handle/1721.1/3331/P-2201-29490295.pdf?sequence=1)|3D problem, constraints consistency criterion. No testing on real data.|
|![][research]|_Gregor J., Rannou F.R._ Three‐dimensional support function estimation and application for projection magnetic resonance imaging // [International journal of imaging systems and technology. 2002 Jan 1;12(1):43-50.](https://doi.org/10.1002/ima.10007)|3D real data testing of [[Karl et al. 1996](https://dspace.mit.edu/bitstream/handle/1721.1/3331/P-2201-29490295.pdf?sequence=1)].|
|![][research]|_Gregor J., Rannou F._ Least-squares framework for projection MRI reconstruction // [In Medical Imaging 2001: Image Processing 2001 Jul 3 (Vol. 4322, pp. 888-899). International Society for Optics and Photonics.](https://doi.org/10.1117/12.431168)|Details of above paper.|

### Other consistent estimators

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Fisher N.I. , Hall P., Turlach B.A., Watson G.S._ On the estimation of a convex set from noisy data on its support function // [Journal of the American Statistical Association. 1997 Mar 1;92(437):84-91.](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.1997.10473605)|Convex set estimation based on periodic smoothing methods.|
|![][research]|_Hall P., Turlach B.A._ On the estimation of a convex set with corners // [IEEE Transactions on Pattern Analysis and Machine Intelligence. 1999 Mar;21(3):225-34.](https://ieeexplore.ieee.org/abstract/document/754588/)|Statistical detection of polygon corners based on support function measurements.|

### Statistical works: LSE for tangient points, tractable and adaptive estimators

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Gardner R.J., Kiderlen M., Milanfar P._ Convergence of algorithms for reconstructing convex bodies and directional measures // [The Annals of Statistics. 2006 Jun 1:1331-74.](https://projecteuclid.org/download/pdfview_1/euclid.aos/1152540751)|First paper about speed of convergence of the estimation algorithm.|
|![][research]|_Gardner R.J., Kiderlen M._ A new algorithm for 3D reconstruction from support functions // [IEEE transactions on pattern analysis and machine intelligence. 2009 Mar;31(3):556-62.](https://pdfs.semanticscholar.org/d2e4/76a632ec55d0b1a7484a5482122e4e047063.pdf)|Another, more efficient way to solve consistency problem in 3D|
|![][research]|_Guntuboyina A._ Optimal rates of convergence for convex set estimation from support functions // [The Annals of Statistics. 2012;40(1):385-411.](https://projecteuclid.org/download/pdfview_1/euclid.aos/1334581747)|Optimal rates, related to [[Gardner et al. 2006](https://projecteuclid.org/download/pdfview_1/euclid.aos/1152540751)].|
|![][research]|_Cai T., Guntuboyina A., Wei Y._ Adaptive estimation of planar convex sets // [arXiv preprint arXiv:1508.03744. 2015 Aug.](https://arxiv.org/abs/1508.03744)|Older, draft preprint version of the below paper.|
|![][research]|_Cai T.T., Guntuboyina A., Wei Y._ Adaptive estimation of planar convex sets // [The Annals of Statistics. 2018;46(3):1018-49.](https://projecteuclid.org/euclid.aos/1525313074)|Estimate that has optimal rate in point-wise and body-wise sense.|
|![][research]|_Soh Y.S., Chandrasekaran V_. Fitting tractable convex sets to support function evaluations // [arXiv preprint arXiv:1903.04194. 2019 Mar 11.](https://arxiv.org/pdf/1903.04194)|Fitting affine images of fixed bodies (e.g. simplicies)|
|![][code]|[yssoh/cvxreg](https://github.com/yssoh/cvxreg)|Code for the above paper|
|![][research]|_Soh Y.S_. Fitting Convex Sets to Data: Algorithms and Applications. [Doctoral dissertation, California Institute of Technology, 2019](https://thesis.library.caltech.edu/11208/1/YongSheng_Soh_2019.pdf)|PhD thesis containing above paper's results and some more|
|![][research]|_Ghosh A. et al_. Max-Affine Regression: Provable, Tractable, and Near-Optimal Statistical Estimation // [arXiv preprint arXiv:1906.09255. 2019 Jun 21.](https://arxiv.org/pdf/1906.09255)|General algorithm for max-affine regression, which is a generalization of SFE|


## Focus of attention
Gregor et al (2002) writes about the usage of KKVW's algorithm of support function estimation for the problem of focus of attention estimation in MRI. However, in further research these authors propose other techinuques, that are less precise, but are more efficient. They are:

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Gregor J., Gleason S.S., Paulus M.J., Cates J._ Fast Feldkamp reconstruction based on focus of attention and distributed computing // [International journal of imaging systems and technology. 2002;12(6):229-34.](https://onlinelibrary.wiley.com/doi/abs/10.1002/ima.10027)|"We aim instead to determine the tightest fitting axial cylinder that has a convex cross-section"|
|![][research]|_Benson T.M., Gregor J._ Three-dimensional focus of attention for iterative cone-beam micro-CT reconstruction // [Physics in Medicine & Biology. 2006 Aug 30;51(18):4533.](http://iopscience.iop.org/article/10.1088/0031-9155/51/18/006/meta)|Development of the above approach.|
|![][research]|_Gregor J._ Data-driven problem reduction for image reconstruction from projections using gift wrapping // [IEEE Transactions on Nuclear Science. 2011 Jun;58(3):724-9.](https://ieeexplore.ieee.org/abstract/document/5753971/)|Continuation of Gregor's research based on gift wrapping algorithm. It approximates focus of attention with intersection of octagon-based cylinders.|

## Probing

Some related works that research probing of convex bodies. Probing is equal to support function measurement in the dual space. See Greschak's thesis for details.

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Cole R., Yap C.K._ Shape from probing // [Journal of Algorithms. 1987 Mar 1;8(1):19-38.](https://www.sciencedirect.com/science/article/pii/0196677487900253)|?_not investigated in detail_; there is also a 1983 technical report with the same title.|
|![][research]|_Greschak J.P._ Reconstructing convex sets. [Doctoral dissertation, Massachusetts Institute of Technology), 1985.](https://dspace.mit.edu/bitstream/handle/1721.1/15285/13620037-MIT.pdf?sequence=2)|Contents the idea that probing of support function is equal to probing of boundary in the dual space.|

## Convex support estimation

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Korostelev A.P., Tsybakov A.B._ Asymptotic efficiency in estimation of a convex set // [Problemy Peredachi Informatsii. 1994;30(4):33-44.](http://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=ppi&paperid=254&option_lang=eng)|Estimation on the plane.|
|![][research]|_Korostelev A.P., Tsybakov A.B._ Minimax theory of image reconstruction // [Springer Science & Business Media, 2012. Vol. 82.](http://download1.libgen.io/ads.php?md5=BE44930DA8C0541D60BD536F90991D23)|Large theoretical monograph.|
|![][research]|_Baldin N., Reiß M._ Unbiased estimation of the volume of a convex body // [Stochastic Processes and their Applications. 2016 Dec 1;126(12):3716-32.](https://www.sciencedirect.com/science/article/pii/S0304414916300369)| Volume estimation.|

TODO: more papers about this area

## Polyhedral approximation

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_McClure D.E., Vitale R.A._ Polygonal approximation of plane convex bodies // [J. Math. Anal. Appl. 1975 Jan 1;51(2):326-58.](http://www.dam.brown.edu/people/dem/publications/1975McClureVitaleJMAA.pdf)|Fundamental best polygonal  approximation in different support function related metrics, and some estimates.|
|![][research]|_McClure D.E._ Nonlinear segmented function approximation and analysis of line patterns // [Quarterly of Applied Mathematics. 1975;33(1):1-37.](https://www.ams.org/journals/qam/1975-33-01/S0033-569X-1975-0463769-X/S0033-569X-1975-0463769-X.pdf)|Contains proofs of most lemmas in [[McClure & Vitale 1975](http://www.dam.brown.edu/people/dem/publications/1975McClureVitaleJMAA.pdf)]|
|![][research]|_Vitale R.A._ Approximation of Convex Set-Valued Functions. [WISCONSIN UNIV-MADISON MATHEMATICS RESEARCH CENTER; 1978 Jan.](http://www.dtic.mil/dtic/tr/fulltext/u2/a054541.pdf)|Bernstein approximation of convex set-valued functions. Not relevant.|
|![][research]|_Бронштейн Е.М._ Аппроксимация выпуклых множеств многогранниками // [Современная математика. Фундаментальные направления. 2007;22(0):5-37.](http://www.mathnet.ru/rus/cmfd83)|Survey about last achievements in polyhedral approximation.|

## Reconstruction from self shadows and reflections

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Hatzitheodorou M., Kender J.R_. An optimal algorithm for the derivation of shape from shadows // [Proceedings CVPR'88: The Computer Society Conference on Computer Vision and Pattern Recognition 1988 Jun 5 (pp. 486-491)](https://ieeexplore.ieee.org/abstract/document/196279)|?|
|![][research]|_Savarese S_. Shape reconstruction from shadows and reflections. [PhD dissertation. California Institute of Technology, 2005](https://thesis.library.caltech.edu/2002/1/savarese_thesis.pdf)|Concave objects reconstruction from self-shadows, and specular shape reconstruction.|
|![][research]|_Savarese S., Chen M., Perona P_. Second order local analysis for 3d reconstruction of specular surfaces // [Proceedings of First International Symposium on 3D Data Processing Visualization and Transmission 2002 Jun 19 (pp. 356-361)](https://ieeexplore.ieee.org/abstract/document/1024083/)|part of above thesis|
|![][research]|_Savarese S., Chen M., Perona P_. Recovering local shape of a mirror surface from reflection of a regular grid // [European Conference on Computer Vision 2004 May 11 (pp. 468-481)](https://authors.library.caltech.edu/47612/1/sav_eccv04.pdf)|part of above thesis|
|![][research]|_Savarese S., Li F.F., Perona P_. Can we see the shape of a mirror? // [Journal of Vision. 2003 Oct 1;3(9):74-.](https://jov.arvojournals.org/article.aspx?articleid=2129844)|part of above thesis|
|![][research]|_Savarese S., Perona P_. Local analysis for 3d reconstruction of specular surfaces // [Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001 2001 Dec 8 (Vol. 2, pp. II-II)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.7.9692&rep=rep1&type=pdf)|part of above thesis|
|![][research]|_Savarese S., Perona P_. Local analysis for 3d reconstruction of specular surfaces — part ii // [European Conference on Computer Vision 2002 May 28 (pp. 759-774).](https://authors.library.caltech.edu/47620/1/eccv_2002_final.pdf)|part of above thesis|
|![][research]|_Savarese S., Rushmeier H., Bernardini F., Perona P_. Shadow carving // [Proceedings Eighth IEEE International Conference on Computer Vision. ICCV 2001 2001 Jul 7 (Vol. 1, pp. 190-197)](http://seminar1.te.ugm.ac.id/pdf/06812_D24C1CFAd01.pdf)|part of above thesis|
|![][research]|_Savarese S., Rushmeier H., Bernardini F., Perona P_. Implementation of a shadow carving system for shape capture // [Proceedings of First International Symposium on 3D Data Processing Visualization and Transmission 2002 Jun 19 (pp. 12-23)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.87.2806&rep=rep1&type=pdf)|part of above thesis|
|![][research]|_Savarese S. et al_. 3d reconstruction by shadow carving: Theory and practical evaluation // [International journal of computer vision. 2007 Mar 1;71(3):305-36.](https://www.researchgate.net/profile/Marco_Andreetto/publication/220660440_3D_Reconstruction_by_Shadow_Carving_Theory_and_Practical_Evaluation/links/0fcfd50a5e15595779000000/3D-Reconstruction-by-Shadow-Carving-Theory-and-Practical-Evaluation.pdf)|part of above thesis|


## Reconstruction from silhouettes

[Scholar query: polyhedron reconstruction from silhouette](https://scholar.google.ru/scholar?hl=en&as_sdt=0%2C5&q=polyhedron+reconstruction+from+silhouette&btnG=)

|Type|Title|Comment|
|---|:---|:---|
|![][research]|_Franco J.S., Boyer E_. Efficient polyhedral modeling from silhouettes // [IEEE Transactions on Pattern Analysis and Machine Intelligence. 2008 Apr 25;31(3):414-27.](https://hal.inria.fr/inria-00349103/document)|?|
|![][research]|_Laurentini A_. How many 2D silhouettes does it take to reconstruct a 3D object? // [Computer Vision and Image Understanding. 1997 Jul 1;67(1):81-7.](https://pdfs.semanticscholar.org/5c57/d481c94295e4aa1c185fc9c74d2fe87c599b.pdf)|?|
|![][research]|_Sinha S.N., Pollefeys M_. Multi-view reconstruction using photo-consistency and exact silhouette constraints: A maximum-flow formulation // [Tenth IEEE International Conference on Computer Vision (ICCV'05) Volume 1 2005 Oct 17 (Vol. 1, pp. 349-356)](https://s3.amazonaws.com/academia.edu.documents/1621852/2uf7t2yslcwyoqo.pdf?response-content-disposition=inline%3B%20filename%3DMulti-View_Reconstruction_Using_Photo-Co.pdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWOWYYGZ2Y53UL3A%2F20190821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20190821T201350Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=52500df9c9401041b5f687d5532c70fbdba6650c222e94d791450f5f5b4fee8c)|?|
|![][research]|_Phothong W. et al_. Quality improvement of 3D models reconstructed from silhouettes of multiple images // [Computer-Aided Design and Applications. 2018 May 4;15(3):288-99.](https://www.tandfonline.com/doi/abs/10.1080/16864360.2017.1397881)|?|
|![][research]|_Merras M., Saaidi A., El Akkad N., Satori K_. Multi-view 3D reconstruction and modeling of the unknown 3D scenes using genetic algorithms // [Soft Computing. 2018 Oct 1;22(19):6271-89.](https://link.springer.com/article/10.1007/s00500-017-2966-z)|?|
