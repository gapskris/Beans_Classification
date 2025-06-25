# Beans_Classification
classifying different types of dry beans using Machine Learning Model,

An agriculture company approaches you with a challenge: they are currently classifying different types of dry beans manually, a process that is labour-intensive, prone to errors and inefficient at scale. They want to automate this classification process using Artificial Intelligence to improve accuracy, reduce operational costs and ensure consistent quality in packaging and distribution.
As a data scientist, your role is to help them build a machine learning solution that can accurately classify bean types based on physical characteristics such as area, perimeter, shape and compactness. By doing this, you'll:
Automate the bean classification process using supervised learning techniques
Help the company reduce manual labour and cost
Improve the speed and reliability of quality control operations
Deliver a scalable solution for real-time classification in industrial settings
This project not only enhances your understanding of supervised machine learning but also demonstrates how AI can be directly applied to Agri-tech and food processing industries for tangible business impact.


Dataset
Use the attached data


Data Dictionary
All configurations (like area, shape and roundness) of data were gathered through camera-based systems using computer vision algorithms—a method commonly used in modern agricultural quality control setups.
Attribute Information:
Area (A): The area of a bean zone and the number of pixels within its boundaries.
Perimeter (P): Bean circumference is defined as the length of its border.
Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.
Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.
Aspect ratio (K): Defines the relationship between L and l.
Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.
Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.
Extent (Ex): The ratio of the pixels in the bounding box to the bean area.
Solidity (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.
Roundness (R): Calculated with the following formula: (4piA)/(P^2)
Compactness (CO): Measures the roundness of an object: Ed/L
ShapeFactor1 (SF1)
ShapeFactor2 (SF2)
ShapeFactor3 (SF3)
ShapeFactor4 (SF4)
Class (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz and Sira)

