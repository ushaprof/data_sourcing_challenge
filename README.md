# data_sourcing_challenge

# This challenge involves preparing a dataset for a prediction system that will help predict Geomagnetic Storms (GSTs).

# These storms are caused by so-called Coronal Mass Ejections (CMEs), which are a massive bursts of plasma emitted from the Sun in irregular intervals, that Earth's magnetic shield fortunately renders harmless to us. However, this interaction with the magnetic shield can still create so-called Geomagnetic Storms (which also cause the Northern and Southern Lights) that can be harmful to electronic devices such as satellites, GPS systems, and essential parts of our powergrids.

# NASA and the Space Weather Prediction Center operate a number of measuring satellites that collect data on CMEs. This data is then used to warn powergrid operators and GPS system operators ahead of time, so that they can make necessary adjustments.

# Preparing CME dataset for a prediction system is done in three steps.

# CME data is requested from NASA API.

# GST data is requested from NASA API.

# Both of these CSV datasets are merged using gst_ActivityID for GST and cme_ActivityID for CME.

# It is shown with info and shape that the number of rows matches both individual DataFrames. 

# A new column is created that shows the difference between startTime_GST and startTime_CME called 'timeDiff'.

# describe() is used to show the mean and median.

# The DataFrame is exported to a CSV file without the index.

