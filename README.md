<h1 align="center"<p>
    <img src="https://github.com/GeostatsGuy/GeostatsPy/blob/master/geostatspy_logo.png?raw=true" width="200" height="200" />
</p></h1>

[![Documentation Status](https://readthedocs.org/projects/geostatspy/badge/?version=latest)](https://geostatspy.readthedocs.io/en/latest/?badge=latest)

<h1 align="center">GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository (0.0.1)</h1>

<h3 align="center">Interactive dashboards to help you over the intellectual hurdles of data science!</h3>

*It is challenging to learn a new Python package. For me, great examples for common workflows are crtical. So I built out over 40 well-documented demonstration workflows that apply GeostatsPy to accomplish common spatial modeling tasks to support my students in my **Data Analytics and Geostatistics**, **Spatial Data Analytics** and **Machine Learning** courses and anyone else learning data analytics and machine learning.* 

### Michael Pyrcz, Professor, The University of Texas at Austin, Data Analytics, Geostatistics and Machine Learning 
#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

***

### Cite As:

Pyrcz, M.J., 2024, GeostatsPyDemos: GeostatsPy Python Package for Spatial Data Analytics and Geostatistics Demonstration Workflows Repository (0.0.1). Zenodo. https://zenodo.org/doi/10.5281/zenodo.12667035

[![DOI](https://zenodo.org/badge/777871341.svg)](https://zenodo.org/doi/10.5281/zenodo.12667035)

***

#### Setup

A minimum environment includes:

* Python 3.7.10 - due to the depdendency of GeostatsPy on the Numba package for code acceleration
* GeostatsPy - I am continuously testing these workflow with the most current version, [GeostatsPy](https://pypi.org/project/geostatspy/)(Pyrcz et al., 2021)
* MatPlotLib - plotting
* NumPy - gridded data and array math
* Pandas - tabulated data
* SciPy - statistics module

The required datasets are available in the [GeoDataSets](https://github.com/GeostatsGuy/GeoDataSets) repository and linked in the workflows.

#### Repository Summary

More than 40 well-documented demonstration workflow for common geostatistical workflows with GeostatsPy. 

* utilizing synthetic data from my [GeoDataSets](https://github.com/GeostatsGuy/GeoDataSets) repository
* small and often 2D examples for fast run times and ease of interpretation
* often used and cited in my courses for repeatable educational content

Common geostatistical workflows that are included:

* data visualization
* distribution transformation
* spatial data debiasing with descustering
* spatial continuity calculation and modeling with variograms
* spatial estimation
* spatial trend modeling
* spatial simulation
* indicator based estimation and simulation
* cosimulation with secondary data
* summarization over multiple simulated realizations
* spatial model checking
* volume variance relations

***

#### Installing GeostatsPy

Firstly, if you haven't installed GeostatsPy, here's the GitHub repository [GeostatsPy GitHub](https://github.com/GeostatsGuy/GeostatsPy/tree/master). GeostatsPy is available on the Python Package Index (PyPI) [GeostatsPy PyPI](https://pypi.org/project/geostatspy/).

To install GeostatsPy, use pip

```console
pip install geostatspy
```
***

#### GeostatsPy Package Dependencies

The functions rely on the following packages:

1. **numpy** - for ndarrays
2. **pandas** - for DataFrames
3. **numpy.linalg** - for linear algebra
4. **numba** - for numerical speed up
5. **scipy** - for fast nearest neighbor search
6. **matplotlib.pyplot** - for plotting
7. **tqdm** - for progress bar
8. **statsmodels** - for weighted (debiased) statistics                

These packages should be available with any modern Python distribution (e.g. https://www.anaconda.com/download/).

If you get a package import error, you may have to first install some of these packages. This can usually be accomplished by opening up a command window on Windows and then typing 'python -m pip install [package-name]'. More assistance is available with the respective package docs.  

#### GeostatsPyDemos Repository Author:

### Michael Pyrcz, Professor, The University of Texas at Austin 
*Novel Data Analytics, Geostatistics and Machine Learning Subsurface Solutions*

With over 17 years of experience in subsurface consulting, research and development, Michael has returned to academia driven by his passion for teaching and enthusiasm for enhancing engineers' and geoscientists' impact in subsurface resource development. 

For more about Michael check out these links:

#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

#### Want to Work Together?

I hope this content is helpful to those that want to learn more about subsurface modeling, data analytics and machine learning. Students and working professionals are welcome to participate.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and / or consulting? I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Professor, Cockrell School of Engineering and The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

***

#### Information about the [GeostatsPy Python Package](https://github.com/GeostatsGuy/GeostatsPy) for Spatial Data Analytics and Geostatistics

The GeostatsPy Package brings GSLIB: Geostatistical Library (Deutsch and Journel, 1998) functions to Python. GSLIB is a practical and extremely robust set of code for building spatial modeling workflows. 

I created the GeostatsPy Package to support my students in my **Data Analytics**, **Geostatistics** and **Machine Learning** courses. I find my students benefit from hands-on opportunities, in fact it is hard to imagine teaching these topics without providing the opportunity to handle the numerical methods and build workflows. Last year, I tried to have them use the original FORTRAN executables and even with support and worked out examples, it was an uphill battle. In addition, all my students and I are now working in Python for our research. Thus, having access to geostatistical methods in Python directly impacts and facilitates the research of my group. This package retains the spirit of GSLIB:

* **modularity** - a collection of standalone functions that may be applied in sequence for maximum flexibility for building workflows
* **minimalistic** - the simplest possible code to support the "look at the code" approach to learning
* **fundamental** - based on the well-established geostatistical theory by avoiding ad hoc methods and assumptions

This package contains 2 parts:

1. **geostatspy.geostats** includes GSLIB functions rewritten in Python. This currently includes all the variogram, distribution transformations, and spatial estimation and simulation methods. I will continue adding functions to support modeling operations for practical subsurface model cosntruction. 

2. **geostatspy.GSLIB** includes reimplimentation of the GSLIB visualizations and low tech wrappers of the numerical methods (note: the low-tech wrapper require access to GSLIB executables).

#### The GeostatsPy Authors

The GeostatsPy package is being developed at The University of Texas in the Texas Center for Geostatistics.

* **Professor Michael J. Pyrcz, Ph.D., P.Eng.** - professor with The University of Texas at Austin. Primary author of the package.

* **Professor Honggeun Jo** - assistant professor with Inha University, South Korea. Author of 3D subroutines, 3D variogram calculation and modeling and wrapper for sgsim for 3D modeling and more! Thank you, Professor Jo!

* **Anton Kupenko** - bug fixes, added docstrings, code refractory for PEP8, removed duplicated functions and variables. Thank you, Anton!

* **Wendi Liu, Ph.D.** - while a Ph.D. student working with Michael Pyrcz at The University of Texas at Austin. Author of 3D subroutines and gammabar method. Also, GSLIB compiles in Mac OSX, and 3D variogram calculation wrapper. Thank you, Dr. Wendi Liu!

* **Alex E. Gigliotti** - undergraduate student working with Michael Pyrcz at The University of Texas at Austin. Established unit testing.  Thank you Alex!

* **Travis Salomaki** - as an undergraduate student research project with Michael Pyrcz at The University of Texas at Austin. Improving package docs. Thank you, Travis!

* **Javier Santos, Ph.D.** - while a Ph.D. student working with Michael Pyrcz at The University of Texas at Austin. Author of the post processing algorithm for summarizing over multiple realizations. Thank you, Javier!

#### Package Inventory

Here's a list and some details on each of the functions available.

##### geostatspy.GSLIB Functions

Utilities to support moving between Python DataFrames and ndarrays, Data Tables, Gridded Data and Models in Geo-EAS file format (standard to GSLIB):

1. **ndarray2GSLIB** - utility to convert 1D or 2D numpy ndarray to a GSLIB Geo-EAS file for use with GSLIB methods 
2. **GSLIB2ndarray** - utility to convert GSLIB Geo-EAS files to a 1D or 2D numpy ndarray for use with Python methods
3. **Dataframe2GSLIB(data_file,df)** - utility to convert pandas DataFrame to a GSLIB Geo-EAS file for use with GSLIB methods
4. **GSLIB2Dataframe** - utility to convert GSLIB Geo-EAS files to a pandas DataFrame for use with Python methods
5. **DataFrame2ndarray** - take spatial data from a DataFrame and make a sparse 2D ndarray (NaN where no data in cell)

Visualization functions with the same parameterization as GSLIB using matplotlib:

6. **pixelplt** - reimplemention in Python of GSLIB pixelplt with matplotlib methods
7. **pixelplt_st** - reimplemention in Python of GSLIB pixelplt with matplotlib methods with support for sub plots
8. **pixelplt_log_st** - reimplemention in Python of GSLIB pixelplt with matplotlib methods with support for sub plots and log color bar
9. **locpix** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods
10. **locpix_st** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods with support for sub plots
11. **locpix_log_st** - pixel plot and location map, reimplementation in Python of a GSLIB MOD with MatPlotLib methods with support for sub plots and log color bar
12. **hist** - histograms reimplemented in Python of GSLIB hist with MatPlotLib methods
13. **hist_st** - histograms reimplemented in Python of GSLIB hist with MatPlotLib methods with support for sub plots

Data transformations

14. **affine** - affine distribution transformation to correct feature mean and standard deviation
15. **nscore** - normal score transform, wrapper for nscore from GSLIB (GSLIB's nscore.exe must be in working directory)
16. **declus** - cell-based declustering, 2D wrapper for declus from GSLIB (GSLIB's declus.exe must be in working directory)

Spatial Continuity

17. **make_variogram** - make a dictionary of variogram parameters to for application with spatial estimation and simulation 
18. **gamv** - irregularly sampled variogram, 2D wrapper for gam from GSLIB (.exe must be in working directory)
19. **varmap** - regular spaced data, 2D wrapper for varmap from GSLIB (.exe must be in working directory)
20. **varmapv** - irregular spaced data, 2D wrapper for varmap from GSLIB (.exe must be in working directory)
21. **vmodel** - variogram model, 2D wrapper for vmodel from GSLIB (.exe must be in working directory)

Spatial Modeling

22. **kb2d** - kriging estimation, 2D wrapper for kb2d from GSLIB (GSLIB's kb2d.exe must be in working directory)
23. **sgsim_uncond** - sequential Gaussian simulation, 2D unconditional wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)
24. **sgsim** - sequential Gaussian simulation, 2D and 3D wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)
25. **cosgsim_uncond** - sequential Gaussian simulation, 2D unconditional wrapper for sgsim from GSLIB (GSLIB's sgsim.exe must be in working directory)

Spatial Model Resampling

26. **sample** - sample 2D model with provided X and Y and append to DataFrame
27. **gkern** - make a Gaussian kernel for convolution, moving window averaging (from Teddy Hartano, Stack Overflow)
28. **regular_sample** - extract regular spaced samples from a 2D spatial model 
29. **random_sample** - extract random samples from a 2D spatial model  
30. **DataFrame2ndarray** - convent spatial point data in a DataFrame to a sparse ndarray grid

##### geostatspy.geostats Functions

Numerical methods in GSLIB (Deutsch and Journel, 1998) translated to Python:

31. **correct_trend** - correct the order relations of an indicator-based trend model
32. **backtr** - GSLIB's backtr function  to transform a distribution
33. **declus** - GSLIB's DECLUS program reimplimented for cell-based declustering in 2D
34. **gam** - GSLIB's GAM program reimplimented for variogram calculation with regular data in 2D
35. **gamv** - GSLIB's GAMV program reimplimented for variogram calculation with iregular data in 2D 
36. **varmapv** - GSLIB's VARMAP program reimplimented for irregularly spaced spatial data in 2D 
37. **vmodel** - GSLIB's VMODEL program reimplimented for visualization of nested variogram models in 2D
38. **nscore** - GSLIB's NSCORE program reimplimented for normal score distribution transformation
39. **kb2d** - GSLIB's KB2D program reimplimented for 2D kriging-based spatial estimation
40. **ik2d** - GSLIB's IK3D program reimplimented for 2D indicator-based kriging estimation
41. **kb3d** - GSLIB's kt3d program reimplimented for 3D kriging-based spatial kriging estimation
42. **sgsim** - GSLIB's sgsim program reimplimented for 2D spatial simulation
43. **postsim** - GSLIB's postsim program reimplimented for summarizing over multiple realizations

More functionality will be added soon.
