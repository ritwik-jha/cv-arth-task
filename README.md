# CV Task 

## 1. Creating a random image 

In this task we create a random image using numpy and show it using matplotlib. 
We know that a gray scale image is just an array with each value being the RGB value of that pixel. So we create a 2D array with values ranging between 0-255. 

We use random module's randint function to randomly place an integer value between 0-255 in each pixel value. Here we have created an image of 100x100 dimension. 

### Code
![image](https://user-images.githubusercontent.com/59885389/121843182-6cdbc100-ccff-11eb-9bc0-3e00c52b5aac.png)

### Output
![image](https://user-images.githubusercontent.com/59885389/121843247-80872780-ccff-11eb-80eb-750aa0e30a90.png)

Here we have obtained an random noisy image. 

## 2. Face swap

In this task we take an image and swap the faces of the characters in the image. 

For this we use harcasscade face detector to get the exact coordinates of the face of the characters. Then we do simple numpy operations to swap the faces. 

### Code
![image](https://user-images.githubusercontent.com/59885389/121843678-597d2580-cd00-11eb-9289-e72ce95abf42.png)
![image](https://user-images.githubusercontent.com/59885389/121843703-6568e780-cd00-11eb-99e7-6e86c4ee0562.png)

### Input/Original Image
![image](https://user-images.githubusercontent.com/59885389/121843827-9c3efd80-cd00-11eb-8c19-654030ae794c.png)

### Output Image (I know its really bad 😑)
![image](https://user-images.githubusercontent.com/59885389/121843940-cc869c00-cd00-11eb-89ca-0b97b8673a06.png)

## 3. Creating a Movie collage using code

In this task we take a few movie posters and combine them to create a collage. 

For this we use pure python code and some basic numpy operations. 

### Code
![image](https://user-images.githubusercontent.com/59885389/121844606-dbba1980-cd01-11eb-902b-6e6062dcecb1.png)
![image](https://user-images.githubusercontent.com/59885389/121844742-0b692180-cd02-11eb-9193-406a63ee7b27.png)
![image](https://user-images.githubusercontent.com/59885389/121844773-1754e380-cd02-11eb-9042-8a6b74586d8c.png)

### Input Images 
![jumanji](jumanji2.jpg)


![skyscraper](skyscraper.jpg)


![gijoe](gijoe.jpg)

### Output
![image](https://user-images.githubusercontent.com/59885389/121845077-8c281d80-cd02-11eb-8bfd-1ad5cec60492.png)



