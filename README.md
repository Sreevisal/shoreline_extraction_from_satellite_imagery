# **Shoreline Extraction from Satellite Imagery**  

This Python code is designed to **automatically extract shorelines** from satellite imagery, particularly **PlanetScope imagery**.  

## **Overview**  
The code is part of the study titled:  
**"Assessing Coastal Dynamics of Ashtamudi Wetland Using PlanetScope Imageries,"**  
which was presented at **INGARSS 2024, Goa**.  

## **Requirements**  
Ensure the following before starting:  
- **PlanetScope Analytic Radiance Scene** is selected for analysis.  
- Clear land-water distinction in the imagery is necessary.  

For downloading Planet imagery, refer to this helpful [video tutorial](https://www.youtube.com/watch?v=XsrclGthh34), which demonstrates the process using **QGIS**.  

## **Post-Processing Instructions**  
After running the algorithm, you may encounter a **double edge problem**. To resolve this:  
1. Apply a buffer of **3 meters** (matching the image resolution).  
2. Use the **Polygon to Centerline** tool to finalize the shoreline extraction.  

## **Example Workflow**  

1. Download PlanetScope imagery.  
2. Preprocess imagery (ensure clear land-water boundaries).  
3. Run this Python code to extract the shoreline.  
4. Post-process the output using the steps above.  

## **Contributions**  
Feel free to raise issues or contribute to the repository!  
