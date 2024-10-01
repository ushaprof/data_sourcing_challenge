# data_sourcing_challenge

# This challenge involves preparing a dataset for a prediction system that will help predict Geomagnetic Storms (GSTs).

# This is done in three steps.

# CME data is requested from NASA API.

# GST data is requested from NASA API.

# Both of these CSV datasets are merged using using gstID and CME_ActivityID for gst and GST_ActivityID and cmeID for cme.

# It is shown with info or shape that the number of rows matches both individual DataFrames. 

# A new column is created that shows the difference between startTime_GST and startTime_CME called 'timeDiff'.

# describe() is used to show the mean and median.

# The DataFrame is exported to a CSV file without the index.

