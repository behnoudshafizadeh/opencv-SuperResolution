## SuperResolution Using DNN module in OpenCV and Colab
>* [introduction](# what is SuperResolution?)
>* installation
>* [Usage](#Usage)
>* your google drive
>* our results
>* Contributing
>* License

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## what is SuperResolution?
>Super resolution encompases a set of algorithms and techniques used to enhance, increase, and upsample the resolution of an input image. More simply, take an input image and increase the width and height of the image with minimal (and ideally zero) degradation in quality.my purpose is increasing the quality of small license-plates for detecting them better than when we dont use superresolution technique in images.

## Installation
>for using SuperResolution module in opencv first see the [following link](https://towardsdatascience.com/how-to-use-opencv-with-gpu-on-colab-25594379945f) and after doing the instructions in it,you will download file that is named `cv2.cpython-36m-x86_64-linux-gnu.so` and you put it in your  `directory` in google drive.

## Usage
>using `.pb` files in `models` files,and the images are in `examples` folder ,for example:
```
$ python super_res_image.py --model models/EDSR_x4.pb --image examples/test.png
--model : The path to the input OpenCV super resolution model
--image : The path to the input image that we want to apply super resolution to
```
## your google drive
![Capture1](https://user-images.githubusercontent.com/53394692/103211182-bcc6f700-491c-11eb-8203-961c03a19330.PNG)
## our results
>after instruction that you run it in colab ,you see the results in google drive as 2 `.png` file `supres` and `resize` :

>>1)resized iamge ==>![resize](https://user-images.githubusercontent.com/53394692/103211709-301d3880-491e-11eb-99b7-85a9ce300e7b.png)

>>2)superres image ==>![supres](https://user-images.githubusercontent.com/53394692/103211713-314e6580-491e-11eb-9fc3-0b63c2542a67.png)

>and you see,the super res image has better quality thab resized image.

## Contributing
>if you face with problems,please contact me by email ==> `behnud.shafizadeh@gmail.com` or my teammate ==> `npourhadi1998@gmail.com`

## License
>[OpenCV Super Resolution with Deep Learning by Adrian Rosebrock](https://www.pyimagesearch.com/2020/11/09/opencv-super-resolution-with-deep-learning/)
