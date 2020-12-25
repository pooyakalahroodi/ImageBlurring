# ImageBlurring
a simplistic python program to blur images with numpy :
1. reads the image With the help of the matplotlib library and saved it as an numpy array (matric) and displayed the image.
2. applies an average filter
3. padds the image on all sides
4. applies the blur filter by convolution
   * Image and av_filter are both numpy arrays
   * The out put is also a numpy array of size [image_height, image_width]
   * The image is padded before convolution
5. plots the original and blurred images side by side by subplots
6. applying the filter more times, makes the image more blurred and faded
