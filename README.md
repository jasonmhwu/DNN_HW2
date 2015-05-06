# DNN_HW2
----------------------------------------------------------------------------------------------------------
##Structured SVM program
----------------------------------------------------------------------------------------------------------
#Environment requirement:
*Linux platform recommended, C/C++ compiler needed.*
#Authors:
*Jason Wu, Larry Tsai, Tom Huang, Ahpan*
		National Taiwan Unversity, Electrical Engineering department.
----------------------------------------------------------------------------------------------------------
	Once all requirements are met, type "**make**" at main directory will compile all executables.
	Shell scripts are provided also, you may need to change some paths in it.
	Sample data are included, type "**make run**" after "**make**", it shall start the whole process of
	structured SVM, the result named "output.kaggle" will be at directory /result
	
#Notes:
---
1.Some directories must be built up before compiling, such as: obj/ bin/ or you can simply enter:__
 *make dir*__

2.The format of features in this program can be generated by a executable: bin/svmFeatureGen.app.__
*Format for this program:*__
*speakerId_utterencename_frameid feat1 feat2 ........*__
*ex:*__
**fmili12_sil0123_1 12.36 1.23 33.54** __
	for detail, you can run this program with no arguments, it will show its usage.__

	For compilation, enter:__
 *make svmGen*__
3.Some example files could help you to run this program.__
	Check them out in__
 *./example/*__ 

4.the core of this program combined two api, svm\_struct and svm\_light, you can see README in
*svm_struct/* for copyright issues.
 
----------------------------------------------------------------------------------------------------------
 
