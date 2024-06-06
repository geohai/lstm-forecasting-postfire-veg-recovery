Quant_Fire_Data_list.shp
  shapefile of all data points (in train, test, and validation splits) attributed with both static and dynamic values. Dynamic values are in string format, where each vaue in the list was concatenated with '_'
  Data are in raw values (i.e., NDVI values range from -2000 - 10,000) and are not standardized and null/255 values have not been dropped. 

all_gdf.pkl
  pickled pandas geodataframe of all points. Data are raw.

.npy files
  all final numpy stacks to use to train/validate/test model. 
  y_train contained y_train1 (ndvi) and y_train2 (lai) stacked. 

x_test_df_storeIDs.csv
  ordered list of FireIDs (references order of sampled in test set .npy arrays)
