# Petavue_Assignment
Preprocessing the Flight and airport datset
Since there are many json and csv files and it will take time load all the dataset , here in this case we first are first working on one  airport file "ATL" and one Flight dataset file name "On_Time_On_Time_Performance_2016_1" and thus getting our new dataset and finding its shape

	FlightDate	Quarter	Year	Month	DayofMonth	DepTime	DepDel15	CRSDepTime	DepDelayMinutes	Origin	Dest	ArrTime	CRSArrTime	ArrDel15	ArrDelayMinutes
0	NaN	            1	  2016	   1  	    6	     1057.0   	0.0	      1100	        0.0	        DFW	   DTW	1432.0	     1438	                                                     0.0	0.0
1	NaN	            1  	2016	   1	      7      	1056.0  	0.0	      1100        	0.0	        DFW	   DTW	1426.0	     1438	0.0              	0.0
2	NaN            	1	  2016	   1       	8      	1055.0	  0.0	      1100        	0.0        	DFW    DTW	1445.0	     1438	0.0	              7.0
3	NaN	            1  	2016	   1      	9	1      102.0  	0.0	      1100	        2.0	        DFW	   DTW	1433.0       	1438	0.0	            0.0
4	NaN            	1	  2016	   1      	10	     1240.0	  1.0	      1100	        100.0      	DFW	   DTW	1631.0	      1438	1.0            113.0


df.shape
(2319, 15)
