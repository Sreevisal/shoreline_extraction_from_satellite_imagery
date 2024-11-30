**shoreline_extraction_from_satellite_imagery**

This python code will help you to automatically extract shoreline from satelite imageries especially planet imagery.
This code is developed as part of work tittled "Assessing Coastal Dynamics of Ashtamudi Wetland 
using PlanetScope Imageries" which is presented at Ingarss 2024 at Goa.

For downloading palnet image reffer this video - https://www.youtube.com/watch?v=XsrclGthh34, which is using QGIS.
We selected PlanetScope Analytic Ortho Scene for analysis which gave clear distinction between land and water.

After using the alhorithm, there will be double edge problem, which we need to apply a buffer of 3 meter (image resolution) and apply  Polygon to centerline tool.
