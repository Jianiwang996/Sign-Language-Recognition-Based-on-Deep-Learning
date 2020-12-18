# Sign-Language-Recognition-Based-on-Deep-Learning
Jianian Wang 605627507

## Executive Summary
Computer Vision has many interesting applications ranging from industrial applications to social applications. It has also been applied in many support for physically challenged people. For deaf- mute people, computer vision can generate English alphabets based on the sign language symbols. Our team aims to design a camera based sign language recognition system. By placing the camera in a fixed place, a user can performing sign in front of the camera, then the system will classify the sign language symbols using the Convolutional Neural Network (CNN). After successful training of the CNN model, the corresponding alphabet of a sign language symbol will be predicted.

### Product
The majority of the work is in installing the tools, data collection from the camera, data processing, and data analysis through Tensorflow CNN model. For hardware, we employ the Arduino nano 33 ble sense and Arducam Mini 2MP Plus camera module, which can be powered by the Arduino board’s power supply. For software, we focus on coding in Python/Tensoflow to build the Convolutional Neural Network model and output results to users. We will use the American Sign Language (ASL) data set for training and testing, which is provided by MNIST and it is publicly available at Kaggle.


## Background 
### Sign Language
####  Introduction
In the communicative hand gesture taxonomies, sign language (SL) is considered as the most organized and structured form out of various gesture categories. Sign language is an important means of communication among hearing impaired and deaf community[1]. Instead of using oral communication and sound patterns, signs in visual space are used by hearing impaired people for communication. The linguistic studies of sign language have started in 1970s [2]. It contains lingual information which includes different symbols and letters. Sign language symbols are able to indicate all the sign parameters that include hand shapes, movement, location and palm orientation.

####  American Sign Language (ASL)
American Sign Language (ASL) is a complete, natural language that has the same linguistic properties as spoken languages, with grammar that differs from English. ASL is expressed by movements of the hands and face. It is the primary language of many North Americans who are deaf and hard of hearing, and is used by many hearing people as well(Wikipedia).

### Sign Language Recognition Using Deep Learning
The flourishing of deep learning technology brings new opportunities for more accurate and real- time sign language recognition.While Neural Networks have been applied to ASL letter recognition in the past with accuracies that are consistently over 90% [3], many of them require a 3-D capture element with motion-tracking gloves or a Microsoft Kinect, and only one of them provides real-time classifications. The constraints imposed by the extra requirements reduce the scalability and feasibility of these solutions[4].

## Design Procedure
### Hardware Implementation
The first goal is the hardware implementation. After purchasing the Arduino nano 33 ble sense board and Arducam Mini 2MP Plus camera online, we need to connect the two parts manually by soldering. To ensure the functionalities of the camera, we will do simple testing through Arduino web editor.
### Aruduino
![image](/Photo/Arduino.jpeg)
### Camera

### Software Implementation
### Database
### CNN Model
#### Training And Testing

## Results
## Strength and Weakness
## Conclusion
## Demo Video
## Reference
[1] Wadhawan, A., Kumar, P. Sign Language Recognition Systems: A Decade Systematic Literature Review. Arch Computat Methods Eng (2019). https://doi.org/10.1007/s11831-019-09384-2.

[2] SBadhe PC, Kulkarni V (2015) Indian Sign Language translator using gesture recognition al- gorithm. In: Proceedings of IEEE international conference on computer graphics on vision and information security (CGVIS), Bhubaneshwar, India, pp 195–200c1.

[3] Singha, J. and Das, K. “Hand Gesture Recognition Based on Karhunen-Loeve Transform”, Mo- bile and Embedded 232 Technology International Conference (MECON), January 17-18, 2013, India. 365-371.

[4] R. Sharma et al. Recognition of Single Handed Sign Language Gestures using Contour Trac- ing descriptor. Proceedings of the World Congress on Engineering 2013 Vol. II, WCE 2013, July 3 - 5, 2013, London, U.K.

