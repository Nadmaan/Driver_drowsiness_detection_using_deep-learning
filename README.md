# Driver_drowsiness_detection_using_deep-learning

Countless people use the highway at all hours of the day and night. Taxi drivers, bus drivers, truck drivers, and long-distance travellers all suffer from sleep deprivation. As a result, driving when sleepy becomes extremely dangerous.

The majority of accidents occur as a result of the driver's tiredness. So, to avoid these accidents, we'll be developing a model using Python, OpenCV, and Keras to create a system that will inform the driver when he gets tired. The implementation of this project idea in actual world could save the life of a random driver and will be extremely useful.

# Dataset Information 
The detection of eyes and their parts, gaze estimation, and eye-blinking frequency are important tasks in computer vision. In last years, we have been solving these tasks in the area of driver's behaviour, which causes the acquiring of a lot of testing data that was acquired in real conditions. Therefore, we introduce the MRL Eye Dataset, the large-scale dataset of human eye images. This dataset contains infrared images in low and high resolution, all captured in various lightning conditions and by different devices. The dataset is suitable for testing several features or trainable classifiers. In order to simplify the comparison of algorithms, the images are divided into several categories, which also makes them suitable for training and testing classifiers.

**Dataset Link** - http://mrl.cs.vsb.cz/eyedataset
![Dataset overview](https://user-images.githubusercontent.com/83595856/185231783-6d78b2f2-236e-4add-9228-d51fff8ce96c.jpg)

# Steps in making the Project 
**1. Downloading the Data** 
**Dataset Link** - http://mrl.cs.vsb.cz/eyedataset

**2. Data Preparation**
 ![Dependencies for data preperation ](https://user-images.githubusercontent.com/83595856/185232951-38a1e89d-8772-4f7f-b836-e14fbb3eef44.jpg)
 ![data prep 1](https://user-images.githubusercontent.com/83595856/185233016-abf05194-6cc8-4606-af35-06d7dfb94c72.jpg)
 ![Data prep 2](https://user-images.githubusercontent.com/83595856/185233093-0f97490c-bf9f-4b50-8b10-7da2139167e6.jpg)
 ![data prep 3](https://user-images.githubusercontent.com/83595856/185233251-bba126ed-8b52-465f-82ee-c88dd2ecaf02.jpg)
 ![Data Prep 4](https://user-images.githubusercontent.com/83595856/185233322-9b62ce10-df66-406f-bf92-5da6c8776fa9.jpg)
 
**3. Image Visualization**

See the random 16 images 
![data visual code](https://user-images.githubusercontent.com/83595856/185233835-82c561c9-e67a-4611-85e7-9cce52cc02ad.jpg)
![16 images](https://user-images.githubusercontent.com/83595856/185233984-eb03f03b-3481-4ed8-9d18-5c4d81096bff.jpg)

**4. Data Augmentation** 
![Data Augumentation](https://user-images.githubusercontent.com/83595856/185234221-176df607-6bea-4472-8529-4154168ee863.jpg)

**5. Model Building**
![Inception v3 model](https://user-images.githubusercontent.com/83595856/185234863-3f6b8024-5392-4e6f-97ba-c1ccae46b9ee.jpg)
![Interations model ](https://user-images.githubusercontent.com/83595856/185234920-1e0c31a3-00e3-42c6-b36c-707f917cbc09.jpg)
![test acc main](https://user-images.githubusercontent.com/83595856/185236174-41b11bc7-bf42-4695-bc19-055cb2739029.jpg)


**6. Har Casceeding for Object Detection**
![Haar cascading ](https://user-images.githubusercontent.com/83595856/185235290-435dd26f-9d17-4138-bd8b-4fc98823215c.jpg)

**7. Alarm Generation**
![Alarm genration](https://user-images.githubusercontent.com/83595856/185235611-bfa6001a-7fe4-4e4f-88d9-987299f03f7b.jpg)








