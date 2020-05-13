# Predicting Research Octane Rating(RON) of gasoline
**Problem statement**: Octane number is one of the most important parameter of gasoline. Gasoline with higher octane numbers is used in high perfomance engines to prevent premature ignition, thus increasing engine wear resistance. However ASTM regulated laboratory method of obtaining octane number requires multimillion dollar equipment to conduct testing that only biggest facilities can afford. With the use of Infrared spectroscopy and machine learning methods it is possible to create models that would comply with ASTM requirements in terms of accuracy, be several times faster and cost efficient compared to original method.

### Example of usual workflow compiled in a single notebook.<br/>
There are dozens of other parameters that I would calculate (Cetane number, aromatics content, distillation characteristics and many others).<br/>
Normally I would store all helper functions in a separate helper_functions.py, however for this example every helper function is inside the nb.<br/>
Because sample size is usually pretty small (<100 samples) it is important to look for influential outliers.<br/>
[Link to properly display nb with all the plots](https://nbviewer.jupyter.org/github/DmitryHCL/IR_ML/blob/master/RON.ipynb)
