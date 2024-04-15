# KSP datathon-
this repo includes our approach to the problem statement of traffic optimisation. 

Team Name: Crosshair

Problem Statement: Traffic Flow Optimization and Congestion Management

Team Size: 4

Team Leader Name: Aditya Narayan Jha

## drive folder with all resources - https://drive.google.com/drive/folders/1Bq0R4jyd0E8tjBAPEYKBR3gAbP2ndUX9?usp=sharing

## demo video link -  https://youtu.be/P9vbIreFvDM
## demo inference sample web app for problem statement - 3 - https://detect.roboflow.com/?model=auto-generated-dataset-7-fbays&version=1&api_key=fZJrRNq8wBaLvAXPRPkk

## IDEA DESCRIPTION - 

### PROBLEM - 1 -  Traffic Monitoring and Analysis:

   - Utilizing Map Engine Services and Drone Footage: The traffic monitoring process begins by leveraging map engine services to provide an initial assessment of congestion levels in various areas. Additionally, drones equipped with cameras are deployed to capture real-time footage of traffic conditions, offering a ground-level perspective for more accurate analysis.

   - Lane-wise Traffic Marking and Vehicle Count Logging: Advanced object detection techniques are applied to the drone footage to mark traffic lanes and accurately count vehicles. This allows for a detailed understanding of traffic distribution and movement patterns.

   - Comparison with Real-time Data from APIs: The recorded data(preferably in a CSV format) from drone footage is compared with real-time traffic data obtained through APIs such as TOMTOM. This comparison is done in order to evaluate the accuracy of the drone analysis footage and provides insights into discrepancies between real time conditions and GPS information 

 -  Additionally: we can store the csv files locally or using a serverless database for future reference that might be required for the referencing the history of   traffic accuracy that was present in certain area.

### PROBLEM -2- Signal Optimization at Junctions:

 - Object Detection-based Monitoring of Traffic Flow: At junctions, object detection technology is deployed to monitor the flow of vehicles. This involves analyzing video footage to track vehicle movements travelling from one lane to the another based upon the queue of vehicles that is standing and number of vehicles that are moving in the flow.
 
  
  - Determination of Optimal Signal Timings: Using the data collected from traffic monitoring, algorithms are employed to determine the most effective signal timings. Factors such as traffic volume, lane occupancy, and historical data are taken into account to optimize signal cycles.

  - Fine-tuning Signal Timings based on Lane Clearance Time: The optimization process includes fine-tuning signal timings based on the average clearance time for each lane. By adjusting signal durations to match lane clearance rates, traffic flow can be further optimized, reducing congestion and improving overall efficiency.

### PROBLEM -3- Bottleneck Detection and Alert System:

   - Identification of Bottlenecks: Bottlenecks such as illegal parking, road encroachments, or poor road conditions are detected through analysis of video footage and manual/automatic annotation of the images. Object detection models are trained to identify these bottleneck factors accurately.

   - Dataset Creation and Model Training: Frames extracted from video footage are used to create a dataset for training object detection models. Annotations are added manually or automatically to label bottleneck factors within the images, facilitating model learning and accuracy.

   - Setting Benchmarks and Issuing Alerts: Benchmarks are established for congestion clearance time based on area-specific factors and historical data analysis. If congestion exceeds these benchmarks, alerts are automatically sent to relevant authorities via messaging services, prompting timely intervention to alleviate traffic bottlenecks and ensure smooth traffic flow.


### additional informations 

Our submission is having the basic development of models and the rest of the post processing for the desired output is still under creation. 

We tend to put our basic functionality and working model prototypes for display for this round of submission. 
There are a lot of integration and improvement that is being required to be done yet and we are trying our best to do so . 

We have already provided our clear architecture and explained in detail about the next possible things we are going to do. We are trying to complete the post processing work as soon as we can.




