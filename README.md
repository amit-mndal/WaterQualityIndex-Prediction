# WaterQualityIndex-Prediction

#Water Quality Index Prediction of River Ganga using Machine Learning.

                                             Objectives
We are given a research paper named, Kosha A. Shah1 Geeta S. Joshi “Evaluation of water quality index for River Sabarmati”, Gujarat, India for a comparative study of river Ganga to measure it’s water quality and label whether it is good for human consumption or not.

In our study the primary approach being used in water quality assessment is the Water Quality Index. The main aim of this project is to implement the machine learning model according to the applied algorithms and which machine learning algorithms' performance is more accurate indicating it perfectly predicts the water quality classifications in the testing set.

Our goal is to develop a predictive model for the Water Quality Index of the River Ganga. By leveraging machine learning algorithms, we intend to establish a robust system that can forecast water quality levels based on relevant environmental parameters.

Water Quality Index (WQI)-
Water quality index (WQI) is one of the most used tools to describe water quality. It is based on physical, chemical, and biological factors that are combined into a single value that ranges from 0 to 100 and involves 4 processes:

(1) Parameter selection

(2) Development of a rating scale to obtain the rating (Vr)

(3) Considering the weightage of each parameter (Wi)

(4) Determining the subindex value (Wi x Vr)

(5) Aggregation of sub-index values to obtain the overall WQI

The Water Quality Index uses six parameters, which are BOD, DO, Conductivity, pH, E.coli. Nitrate. To obtain the WQI value, all parameters needed to be converted first into subindices (SI), namely SIBOD SIDO, SIEC, SIpH, SIN and SIE.coli. Then, the calculation of WQI was performed by substituting all sub indices of the six parameters into the WQI formula. 

          # WQI = ∑ Sli

Where, WQI is the Water Quality Index. n is the number of water quality parameters

Where, "Sli" is the subindex rating..

         # Sli = Wi x Vr

"Wi" is the unit weight

"Vr" is the rating which can be obtained from a rating scale based on all the parameters



