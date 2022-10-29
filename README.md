# 2017
library("ggplot2")
library("plotly")
library("ncdf4")
library("ncdf4.helpers")
library("PCICt")

weather_filepath <- paste0("G:/Shared drives/VZRG_TAMU/Evan/GPCP_Precipiation_2017.nc")
weather_output <- nc_open(weather_filepath)
print(weather_output)
