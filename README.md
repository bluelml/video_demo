# video_demo
This is snowsense API demo, used to trace and detect face.
It was tested on Windows 10. Not verified on Linux or Android yet.
Before running, you should download snowsense python SDK into root directroy. 

# Disadvantage
Call the server API is very slow, so there is big latency. 

# Optimize in the feature
Use openCV to trace for saving server resource and snowsense API to detect for accuracy. 
Need support multi-threads on Raspberry to distribute on CPUs which can handle about 5f/s individully and total speed is about 20f/s. 
