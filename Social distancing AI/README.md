# Social-Distancing-Analyser-COVID-19
An AI tool to prevent spreading of coronavirus (COVID-19) by using computer vision on video surveillance.
A social distancing analyzer AI tool to regulate social distancing protocol using video surveillance of CCTV cameras and drones. Social Distancing Analyser to prevent COVID19

Social Distancing Analyser automatically detects the extent to which social distancing protocols are followed in the area.
Deploying it on current surveillance systems and drones used by police to monitor large areas can help to prevent coronavirus by allowing automated and better tracking of activities happening in the area. It shows analytics of the area in real time. It can also be used to alert police in case of considerable violation of social distancing protocols in a particular area. 

 
 
 
#### v1.0 output:

![](output.gif)



## Features:
* Get the areal time analytics such as:
   - Number of people in a particular area
   - Number of people in high risk
   - The extent of risk to a particular person.
* Doesn't collect any data of a particular person
* Stores a video output for review

## Installation:
* Fork the repository and download the code.
   -```gh repo clone Anshnrag02/Vihaan-Covid-Project/Social%20distancing%20AI```
* Install all the required libraries:
   -```pip install -r requirements.txt```
   
* Download the following files and place it in the same directory
   - https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
   - https://pjreddie.com/media/files/yolov3.weights
* For slower CPUs, use yolov3-tiny (link in the code comments)
* Install all the dependenices
* Run social_distancing_analyser.py 
