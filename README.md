# ASU Course

CSE 546 - Cloud Computing

# Image-Processing-as-a-Service

Implement AWS IaaS infrastructure to create and support an Image Processing application for processing images uploaded by the user.

The user will upload multiple images on the application running on EC2 Instance at AWS and will be able to get the image processing result for each image he/she has uploaded.
Once the user uploads images on Web Tier, then he/she needs to get the result for all the uploaded images without any loss of result.
Along with this, the user needs to get the result in a minimum acceptable time frame, as well as the App Tier program needs to handle all the requests of the user. For this, we are using Autoscaling in EC2, to meet the demands of the user. This is important because users should get the results as quickly as possible, and our architecture should be able to handle the demand in real time.


![image](https://user-images.githubusercontent.com/28748273/197423848-641bc322-9e75-41ed-842b-617b7c7efcbe.png)
