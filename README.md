# Laboratory 2 Simple Spatial Objects in Python 

## How to set up the virtual environment
The virtual environment set up, first create a folder named, and open it in Visul Studio Code as the project root. Next inside the folder create/ adding a subfolders (data,output,src,tests) and files (README.md, requirement.txt, data/points.csv, src/spatial.py).
Next open the VS Code Terminal and create a virtual environment with python -m venv .venv, then activate it ./.venv/scripts/activate on windows or source.venv/bin/activate.
# Description 

## Reflections 
Respond to the following and write a section in your README.md
1. Object vs Geometry
In this activity,  the object is the csv points, and the geometry is the latitude and longitude, create a ValueError. 
How did modeling points as objects change the way you thought about the data compared 
to treating them as rows in a table. 
Both points has the same ID and information, but the different is the point as rows, like a spreadsheet where the geometry is not a spatial compare to points as objects they have entity with geometry and attributes that can interact and measure. 
Responsibility 
Which behaviors belonged in Point, which belonged in PointSet, and which belonged in the 
runner script? Give one concrete example. 
In this laboratory, the comparison  of the two scripts,  In class point it is creating points,  calling methods and the responsibility is what the rules and structure is (id, lon, lat, name, tag) while when the class point is belong to runner script but in this laboaratory, i was failed to run the script in run_lab.py,  but I noticed when I run in demo.py the class is defining, enforcing rules, and ensuring correctness. 
Modeling Insight 
How did separating geometry, meaning, and behavior make the spatial logic easier (or 
harder) to understand?
This is the example that I can use this activity  Compute the Haversine distance between two lon/lat pairs in meters. 

## Challenge encountered I cannot run the challenge, due to the path of my data is not call or read when I processing. 