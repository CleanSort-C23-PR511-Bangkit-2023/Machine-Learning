# Machine-Learning
This repository contains the code to detection and waste classification.
CleanSort APP is a smart waste detection and classification application that utilizes the power of cloud computing to enhance waste management processes. 
The app is designed to identify and categorize different types of waste materials accurately. 
It provides users with disposal guidelines based on the specific waste category, promoting responsible waste disposal practices.

## Overview
![image](https://github.com/CleanSort-C23-PR511-Bangkit-2023/Machine-Learning/assets/96606602/15fdb320-afe9-4f55-a8c8-a75a88a981b7)
![image](https://github.com/CleanSort-C23-PR511-Bangkit-2023/Machine-Learning/assets/96606602/63b28f4c-b09a-4f91-95e3-133af2956c1e)

![sampah2](https://github.com/CleanSort-C23-PR511-Bangkit-2023/Machine-Learning/assets/126807857/06fd9697-34ce-4d9b-8583-655e24309830)
![0w](https://github.com/CleanSort-C23-PR511-Bangkit-2023/Machine-Learning/assets/126807857/9cbae19c-5a91-4bbc-8dd5-55aac3615535)

**program flow is as follows:**
1. Register/Login :  We opens the application and is prompted to register/log in
2. We sees the home screen with options to choose between taking a photo of the trash or reading the explanation about organic/recyclable waste.
3. If we select Explanation, the application displays information explaining organic and recyclable waste
4. If we select take a photo of the trash, the application opens the mobile camera.
5. The application sends the trash photo to the server for processing and server receives the photo from We and uses the trash detection model to analyze the image and classify the trash as organic or recyclable.
6. The application receives the classification prediction from the server. We sees the prediction result on our mobile screen.The prediction output includes the type of trash (organic or recyclable) and recommendations for proper handling.

For this project, we first use a Hierarhical Data Format 5 (H5) and generate our own dataset. From the datasets we create, we train our model and get 85% accuracy. Refers to https://github.com/CleanSort-C23-PR511-Bangkit-2023/Machine-Learning/blob/master/CNN_FIX.ipynb
