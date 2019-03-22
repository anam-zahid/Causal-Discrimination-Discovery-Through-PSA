# Causal Discrimination Discovery Through Propensity Score Analysis

________________________________________________________________

			Python Version Dependency
________________________________________________________________

	1-  Python version 3.6.3
	2-  Anaconda Spyder version 3.2.4  

________________________________________________________________

			Package Dependencies
________________________________________________________________

### We need to install the following packages

	1-  pandas
	2-  ExtraTreesClassifier from sklearn.ensemble
	3-  LogisticRegression from sklearn.linear_model
	4-  numpy
	5-  time
	6-  threading
	7-  math
	8-  matplotlib.pyplot
	9-  tree from sklearn
	10- StringIO from sklearn.externals.six
	11- pydotplus (sometimes graphviz has to be installed seperately)

_________________________________________________________________

			Input File and Basic Execution
_________________________________________________________________

	1-  Input file needs to be in a csv format
	2-  Input file should contain two binary attributes "class" & "sensitive" with the following values
	    class:
	    	positive class (e.g., yes) --> 1
	    	negative class (e.g., no) --> 0
	    sensitive:
	    	treatment group (e.g., male) --> 1
	    	control group (e.g., female) --> 0
	3-  Keep the input file in the same directory as the python files or else you would have to set an 
		absolute/relative path in the instructions.py file
	4-  Open instruction.py
	5-  Add file name as a parameter to the call of "CDDTPSA" function at the bottom of the code
	6-  Code has the following set of files
		instructions.py
		Propensity_infogain.py
		Propensity_chisquare.py
		NormalizeAndSplit
		KNN.py
		Nuteralize_Instances.py
		Create_Bins.py
		Probability_Graph.py
		RDC_RDNC_Graph.py
		Group_Comp_Graph.py
		Regression_Tree.py
	7-  Output would contain 6 graphs and 2 trees in PDF format in the same folder else you would have to set 
	an absolute/relative path in the last four files

