# Determination of the most profitable oil production region

Goal:
* Decide in which region to extract oil. Build a machine learning model that will help determine the region where mining will bring the most profit with the least risk of loss.
 
Description:
* The production company needs to decide where to drill a new well. Collected characteristics of oil sample for wells: oil quality and volume of its reserves in three regions. The characteristics for each well in the region are already known. A model has been built to predict the volume of reserves in new wells. Wells with the highest estimated values were selected. The regions with the maximum total profit of the selected wells have been identified. A model has been built to determine the region where production will bring the greatest profit. Potential profits and risks were analyzed using Bootstrap technique.

Data: 
* Oil samples from three different regions. The characteristics for each well in the region are already known.

Data Description: 
* *id* - the unique identifier of the well;
* *f0, f1, f2* - three signs of points (it doesn't matter what they mean, but the signs themselves are significant);
* *product* - the volume of reserves in the well (thousand barrels).

Libraries:
* Pandas, sklearn, math, numpy, Seaborn, Matplotlib, SciPy, Bootstrap, Machine Learning

Tags:
* Bootstrap, machine learning, Python, Pandas, Numpy, Matplotlib, Sklearn, gradient boosting, regression

Project status:
* Completed
