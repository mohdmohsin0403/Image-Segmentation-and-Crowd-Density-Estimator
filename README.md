# Image-Segmentation-and-Crowd-Density-Estimator

Image segmentation is a commonly used technique in digital image processing and analysis to partition an image into multiple parts or regions, often based on the characteristics of the pixels in the image. It is a method in which a digital image is broken down into various subgroups called Image segments which helps in reducing the complexity of the image to make further processing or analysis of the image simpler. Segmentation in easy words is assigning labels to pixels.

![image](https://user-images.githubusercontent.com/78999231/195501724-f899adb3-000c-4c24-aecc-7f54abe6a796.png)

Crowd density refers to the number of objects within a unit area, such as people per square meter. Density is important to determine the maximum occupancy of a room or building to address safety concerns. Crowd density estimation is a hot issue in the analysis of crowd abnormal behavior. At present, the crowd density is calculated by the ratio of population and area. However, these methods ignore the influence of monitoring perspective and local crowd distribution in the selection and processing of area.

![image](https://user-images.githubusercontent.com/78999231/195502092-cbb4d818-07e6-470d-b869-9c30d11f87a3.png)

## About the dataset

The [Dataset](https://drive.google.com/drive/folders/16LbuCsSrQs2TSvqFwekzIN0xgBzv6I68?usp=sharing) can be downloaded from here and can also pe seen in release section.

The Shanghaitech dataset is a large-scale crowd counting dataset. It consists of 1198 annotated crowd images. The dataset is divided into two parts, Part-A containing 482 images and Part-B containing 716 images. Part-A is split into train and test subsets consisting of 300 and 182 images, respectively. Part-B is split into train and test subsets consisting of 400 and 316 images. Each person in a crowd image is annotated with one point close to the center of the head. In total, the dataset consists of 330,165 annotated people. Images from Part-A were collected from the Internet, while images from Part-B were collected on the busy streets of Shanghai.

## Code

Firstly required library such as numpy, pandas and os are imported. Then the dataset for the same is loaded.

![image](https://user-images.githubusercontent.com/78999231/195502625-3bdab904-c0f9-4677-8cd2-e65aa88e5525.png)

Then listing of all the files is done, firstly we have done it for part A dataset

![image](https://user-images.githubusercontent.com/78999231/195502712-a3994f4a-ca8a-45dd-9ae3-60c26858ff8f.png)

After this the image path and all is given and a particular image is selected. We have selected this particular image:

![image](https://user-images.githubusercontent.com/78999231/195502946-b5a72720-21e0-434a-8bab-dbf90fa3add9.png)

After that the density for the same image is calculated.

![image](https://user-images.githubusercontent.com/78999231/195503011-4dc2053c-b168-4123-b213-f275030e31dd.png)

And then while using numpy sum function we will estimate the crownd.

![image](https://user-images.githubusercontent.com/78999231/195503119-55732de0-82d5-4c31-8f40-4c0a07e7ee12.png)

