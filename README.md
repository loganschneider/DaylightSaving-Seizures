# DaylightSaving-Seizures
Analysis of DST-related seizure incidence in Seizure Tracker data from 2008-2016 with over 1.2 million documented seizures for publication in Epilepsia: Schneider LD, Moss RE, Goldenholz DM. Daylight saving time transitions are not associated with increased seizure incidence. Epilepsia. 2019 Mar 19. doi: 10.1111/epi.14696.

There are multiple files now:
  -DSTclean.Rmd is the R Markdown for cleaning (takes a couple days for some of the loops)
  -DSTanalysis.Rmd then loads the cleaned csv files and runs the main analyses
  -DSTanalReviewer.Rmd adds further analyses requested by the statistical reviewer (#3): Bayesian methods and GLMMs
  -DSTanalysis4pub.Rmd generates figures with the Epilepsia color scheme for final publication
  -DSTinfradian.Rmd is just a fun aside using time series analysis methods (autoregression, etc.) to demonstrate infradian (7-day, circannual, etc.) patterns in the data as well
