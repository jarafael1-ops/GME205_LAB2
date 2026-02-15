# Project Title: Simple Spatial Objects in Python 

## How to set up the virtual environment
To set up the virtual environment, first create a new folder named gme205-lab2 and open it in Visual Studio Code as your project root. Inside the folder, build the required structure by adding subfolders (data, output, src, tests) and files (README.md, requirements.txt, data/points.csv, src/spatial.py, src/run_lab2.py, src/demo.py, tests/test_spatial.py). Next, open the VS Code terminal and create a virtual environment with python -m venv .venv, then activate it (.\.venv\Scripts\activate on Windows or source .venv/bin/activate . In VS Code, select the .venv interpreter to ensure scripts run in the correct environment. With the environment active, install the required libraries using pip install pandas matplotlib, confirm installation with pip list, and save dependencies into requirements.txt using pip freeze > requirements.txt. Finally, initialize Git with git init, add a .gitignore to exclude .venv/,** __pycache__/**, and output/, then commit everything with git add. && git commit -m "Initial Lab 2 setup". This gives you a clean, reproducible workspace with version control ready for the lab.


## How to run the Python Scripts
To run the Python scripts in the Lab 2 project, first activate the virtual environment so that all dependencies are available. On Windows, use .\.venv\Scripts\activate,use source .venv/bin/activate. Once the environment is active, navigate to the project root folder gme205-lab2 in your terminal. From there, you can run any of your scripts with the python command, for example, python src/run_lab2.py to execute the main lab script, python src/demo.py for the demo, or python src/spatial.py to run the spatial module directly. To check your tests, use python -m unittest tests/test_spatial.py or run all tests with python -m unittest discover tests. Any outputs generated will appear in the output/ folder, while printed results will show in the terminal. This workflow ensures your scripts run consistently inside the reproducible environment you set up.


## Reflections 
Respond to the following and write a section in your README.md
1. Object vs Geometry
In this activity,  the object is the csv points, and the geometry is the latitude and longitude, create a ValueError. 
How did modeling points as objects change the way you thought about the data compared 
to treating them as rows in a table. 
Both points has the same ID and information, but the difference is the point as rows, like a spreadsheet where the geometry is not a spatial comparison to points as objects, they have an entity with geometry and attributes that can interact and measure. 
Responsibility 
Which behaviors belonged in Point, which belonged in PointSet, and which belonged in the 
runner script? Give one concrete example. 
In this laboratory, the comparison  of the two scripts,  In class point it is creating points,  calling methods and the responsibility is what the rules and structure is (id, lon, lat, name, tag) while when the class point is belong to runner script but in this laboaratory, i was failed to run the script in run_lab.py,  but I noticed when I run in demo.py the class is defining, enforcing rules, and ensuring correctness. 
Modeling Insight 
How did separating geometry, meaning, and behavior make the spatial logic easier (or 
harder) to understand?
This is the example that I can use this activity  Compute the Haversine distance between two lon/lat pairs in meters. 

## Challenge encountered I cannot run the challenge, due to the path of my data is not call or read when I processing. 
