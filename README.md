# CS4375 README
23Spring_CS4375
NetID: ZXC180008

Assignment 1 README File


!!!!!!!!!
This project read an online host data source, and generate an linear regression medel using Gradient Descent
1. Find the data source
2. Host in public location
3. create two python files using google colab part1.py & part2.py
4. part1 read csv url and calculate the model through two gradient descent function
   Example various parameter are learning rate and n iteration when do the testing
5. Apply the model you created in the previous step to the test part of the
dataset. Report the test dataset error values for the best set of parameters
obtained from previous part. 
6. In part 2, we build linear regression model using ML Libraires.
*7. Keep a log file of your trials indicating parameters used, training
error, and test error. 


Submission File includes:

README.MD
part1.py
part2.py
Report.pdf
Cover_Page.pdf

Database choose from https://archive.ics.uci.edu/ml/datasets.php. --> Abalone

Data is host in public location, in my own Github file

Database file contains:

abalone.data
abalone.names
Index

#DATABASE Explanation:

Title of Database: Abalone data

Number of Instances: 4177

Number of Attributes: 8

Attribute information:


	Name		Data Type	Meas.	Description
	----		---------	-----	-----------
	Sex		nominal			M, F, and I (infant) # AFTER convert to numerical category, I set the value to 0,1,2
	Length		continuous	mm	Longest shell measurement
	Diameter	continuous	mm	perpendicular to length
	Height		continuous	mm	with meat in shell
	Whole weight	continuous	grams	whole abalone
	Shucked weight	continuous	grams	weight of meat
	Viscera weight	continuous	grams	gut weight (after bleeding)
	Shell weight	continuous	grams	after being dried
	Rings		integer			+1.5 gives the age in years


 Class Distribution:

	Class	Examples
	-----	--------
	1	1
	2	1
	3	15
	4	57
	5	115
	6	259
	7	391
	8	568
	9	689
	10	634
	11	487
	12	267
	13	203
	14	126
	15	103
	16	67
	17	58
	18	42
	19	32
	20	26
	21	14
	22	6
	23	9
	24	2
	25	1
	26	1
	27	2
	29	1
	-----	----
	Total	4177

