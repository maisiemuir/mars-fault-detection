# mars-fault-detection

├── data
│   ├── 1_Upload_Raw_Data_to_GCP.ipynb
│   └── 2_Data_Transfer_GCP_to_EE.ipynb
│   └── 3_Data_Processing_EE.ipynb 
│   └── 4_Data_Export_EE_to_GCP_TFRecord.ipynb
│   └── 5_Modelling.ipynb
│   └── tsv_files
│       └── mars_elevation_data.tsv
└── notebooks
    ├── Data_Visualisation_EE.ipynb
    └── Data_Visualisation_GCP.ipynb

Earth Engine folder structure:
- mars
    - features
        - {feature_name}
            - pre
            - post
    - labels
        - {label_name}
            - pre
            - post
