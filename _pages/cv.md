---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in [SEGS](https://segs.shnu.edu.cn/), Shanghai Normal University, 2019-2023
  
Skills
======
* [Python](https://www.python.org/)
  * [Gdal](https://gdal.org/): Processing raster data
  * [Numpy](https://numpy.org/): Data preprocessing
  * [Matplotlib](https://matplotlib.org/): Drawing plots and figures
  * [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/): Downloading files
  * Machine learning
    * [Scikit-learn](https://scikit-learn.org/stable/index.html): Regression and prediction
    * Deep learning
      * [TensorFlow](https://numpy.org/): Training and predicting data
* CFD
  * [ANSYS Fluent](https://www.ansys.com/zh-cn/products/fluids/ansys-fluent): Field simulation
    * [RANS(Reynolds Average Navier-Stokes)](https://blog.csdn.net/weixin_42562856/article/details/106515992): Turbulence model
    * [VOF(Volume of Fluid)](https://zhuanlan.zhihu.com/p/165649922): Simulating waves
    * [UDF(User Defined Functions based on C++)](https://zhuanlan.zhihu.com/p/361705789): Source and think terms
    * [UDM(User-Defined Memory)](https://max.book118.com/html/2019/0706/7022055123002036.shtm): Computational memory
  * [Siemens Star-CCM](https://plm.sw.siemens.com/en-US/simcenter/fluids-thermal-simulation/star-ccm/)
    * [CAD Processing](https://max.book118.com/html/2018/1022/7135052164001153.shtm): Geomatry processing
    * [Meshing](https://community.sw.siemens.com/s/article/A-new-user-s-guide-to-STAR-CCM-simulation-Part-3-5-Meshing)
    * Simluation
  * Tecplot
* GIS & RS
  * [ESRI ArcGIS](https://www.esri.com/en-us/arcgis/about-arcgis/overview)
  * [SuperMap](https://www.supermap.com/)
  * [GeoDa](https://geodacenter.github.io/)
  * [ENVI](https://envi.geoscene.cn/)
* Others
  * [IBM SPSS](https://www.ibm.com/spss)
  * [Matlab](https://ww2.mathworks.cn/products/matlab.html?requestedDomain=zh)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
