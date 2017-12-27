# Letter-Recognition

Letter Recognition from a Photo with Machine Learning in Python.

Libraries used:
- Numpy
- Pandas
- Matplotlib
- Seaborn

Dataset contains the following:
- lettr	capital letter	(26 values from A to Z)
-	x-box	horizontal position of box	(integer)
-	y-box	vertical position of box	(integer)
- width	width of box			(integer)
-	high 	height of box			(integer)
-	onpix	total # on pixels		(integer)
-	x-bar	mean x of on pixels in box	(integer)
-	y-bar	mean y of on pixels in box	(integer)
-	x2bar	mean x variance			(integer)
-	y2bar	mean y variance			(integer)
-	xybar	mean x y correlation		(integer)
-	x2ybr	mean of x * x * y		(integer)
-	xy2br	mean of x * y * y		(integer)
-	x-ege	mean edge count left to right	(integer)
-	xegvy	correlation of x-ege with y	(integer)
-	y-ege	mean edge count bottom to top	(integer)
-	yegvx	correlation of y-ege with x	(integer)

Dataset is splitted into Train and Test Set so as to train our Model on Train Set and then use Test Set to evaluate the performance the Model.

Classification Algorithms used here:
- Logistic Regression
- SVM
- Random Forest

 Model's performance is evaluated using:
 - Confusuin Matrix
 - Classification Report
