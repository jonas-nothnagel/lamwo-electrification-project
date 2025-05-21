# Perform several ML tasks with data to support green energy site identification

This folder contains several machine learning approaches for identifying green minigrids from mostly satellife imagery.

**[`village_feature_extraction.ipynb`](#village_feature_extraction)**  
   This script mainly extracts features from several datasets with respect to villages in Lamwo. We use this village data to build the machine learning algorithms for doing several tasks. 

   It extracts the following features per village: 
   ['village_id', 'candidate_minigrids', 'existing_minigrids', 'facilities',
       'grid_extension', 'existing_grid', 'distance_to_grid', 'mean_ndvi',
       'mean_wind_speed', 'mean_pvout_solar_radiation', 'total_population',
       'mean_biomass', 'building_count', 'permanent_building_count',
       'educational_facilities', 'health_facilities', 'social_facilities',
       'services', 'primary_roads', 'secondary_roads', 'tertiary_roads',
       'unclassified_roads', 'percentage_crop_land', 'percentage_built_area',
       'contains_protected_area', 'protected_area_name',
       'electrification_strategy']