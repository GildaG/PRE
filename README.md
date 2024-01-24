This plots PRE (that is obtain from the smoothed IVM_ion vel merdional) vs UT and longitude (version 2).
ICON has a 27-degree inclination and focusing on -20 to 20 degrees magnetic latitude, the number of PRE observations per day will likely be fewer than the number of orbits per day (15)
and this number can vary day-to-day.
The smoothed IVM_ion vel meridional is calcualted:
1- identify and remove irregularities from the data (using moving std higher than 10000)
2- Missing data points are interpolated
3- A Savitzky-Golay filter is applied to the data for smoothing purposes
4- It avoids smoothing the edges of the dataset.
ICON_L27_RPA_Flag and ICON_L27_DM_Flag is equal to 0 to guarantee IVM data quality. 
