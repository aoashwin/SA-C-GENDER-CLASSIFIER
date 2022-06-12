# SA-C-GENDER-CLASSIFIER
# Algorithm
1. To classify the gender of a person use the DeepFace library.
2. DeepFace library is developed based on deep learning algorithms.
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the imported image.
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable.
7. Finally print the prediction using this algorithm.

## Program:
```
/*
Program to implement 
Developed by   : ASHWIN A O
RegisterNumber :  212220230005
*/
```

1. CODE :
```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('imp.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('kaleesi.jpeg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:
![Screenshot 2022-06-12 191624](https://user-images.githubusercontent.com/75235601/173236308-7390cb5c-a2f4-48da-8e61-e227de2ba434.jpg)
![Screenshot 2022-06-12 191638](https://user-images.githubusercontent.com/75235601/173236318-a04755f2-ce91-41fb-8299-644e610d9afb.jpg)


2. DEMO VIDEO YOUTUBE LINK:
https://www.youtube.com/watch?v=QMPplZCn8W8&list=LLM00gNhKE-WSIwizgJYdIdw

