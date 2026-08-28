# Project Title 
GmE 205 — Laboratory 1: Computational Thinking Foundations: Python, VS Code, and GitHub

# How to set up the virtual environment 
Open the VS Code terminal (Terminal → New Terminal) and run
py -m venv .venv 
.\.venv\Scripts\activate

# How to run Python scripts 
Press Ctrl + Shift + P (or Cmd + Shift + P on Mac) 
Search for Python: Select Interpreter 
Choose the interpreter inside the .venv folder

# Edited on GitHub web interface
# Run Instructions

# ===========================================================================

# Reflection

Abstraction: What did you choose to inspect, and why? 

I chose to inspect the data quality of latitude and longitude values of a given set of points (missing or invalid values), and if the said points fall within the bounds of UP campus. This is to ensure that the dataset is valid and reliable, and that using it for further analysis will not result in errors or inaccurate spatial results. 

Representation: What assumptions are you making about the CSV and coordinates?

My assumption about the CSV and coordinate data is that the coordinates do not necessarily represent any specific real-world objects or features. Given the context of the activity, I am treating the data simply as latitude and longitude values that fall within the geographic bounds of the UP campus. 
	
Responsibility: What should the script check automatically vs what a human should check?

The script should perform data quality checks that are objective and rule-based, i.e., checks that can be executed through programming. Humans, on the other hand, should check the quality of the data based on the context of its use.

Scale: What problems might happen if the dataset becomes very large? 

If the dataset becomes very large, the script may take a longer time to process the data and may even require higher computing capabilities.

# ==============================================================================