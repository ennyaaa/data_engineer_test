# data_engineer_test
This repository contain 2 Job which developed by Talend Open Studio Data Integration

1. Generate_Data
2. Display_and_Export_Data

Requirement :
- Installed JDK
- Command Line

Build Job Documentation:
https://help.talend.com/r/QrWkwPvKmKybs~JNLeBt3Q/qbnEwchhptoTZ38u6UCV~g

Run Program from UNIX Command Line:
1. Generate_Data
    - Go to build job directory
    - Unzip the build job
      command : unzip Generate_Data_0.1.zip
    - Run the job
      command : sh Generate_Data_run.sh
    - Data Output Location : inside job directory
      
2. Display_and_Export_Data
    - Go to build job directory
    - Unzip the build job
      command : unzip Display_and_Export_Data_0.1.zip
    - Run the job
      command : sh Display_and_Export_Data.sh --context_param input_file="Directory/filename.zip" --context_param filter_range_amount_min=10 --context_param filter_range_amount_max=100 --context_param filter_timestamp_min="2019-01-01" --context_param filter_timestamp_max="2019-12-31" --context_param filter_percentile=94
      
      NB : you can change the context_param value
      
![image](https://user-images.githubusercontent.com/23351981/131258036-fbea8a2c-e5dd-43df-8865-9abefd62a4b6.png)

~ You can also run using windows command prompt using .bat file

    
