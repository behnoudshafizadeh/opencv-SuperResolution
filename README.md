# SuperResolution Using DNN module in OpenCV and Colab
* introduction
  * [behnoud](#gpu)
  * memory
* tabels of contents
# introduction
# gpu
```
$ behnoud

```
![resize](https://user-images.githubusercontent.com/53394692/103181319-290e1000-48b5-11eb-9adb-5e8858969e79.png)
`shafizadeh`

## Instalation
for using SuperResolution module in opencv first see the [following link](https://towardsdatascience.com/how-to-use-opencv-with-gpu-on-colab-25594379945f) and after doing the instructions in it,you will download file that is named `cv2.cpython-36m-x86_64-linux-gnu.so` and you put it in your  `directory` in google drive.

## Usage
using `.pb` files in `models` files,and the images are in `examples` folder ,for example:
```
$ python super_res_image.py --model models/EDSR_x4.pb --image examples/test.png
--model : The path to the input OpenCV super resolution model
--image : The path to the input image that we want to apply super resolution to
```
## Contributing
if you face with problems,please contact me by email ==> `behnud.shafizadeh@gmail.com` or my teammate ==> `npourhadi1998@gmail.com`

## License
[OpenCV Super Resolution with Deep Learning by Adrian Rosebrock](https://www.pyimagesearch.com/2020/11/09/opencv-super-resolution-with-deep-learning/)
