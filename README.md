# GrayImageColorMap
**Author:** Lenin G. Falconi
Jupyter Notebook to explore Color Mapping in Gray Images. Matplotlib and imshow in matlab allow the use of seudo color in single channel images (gray images). Image is represented in the color map of HSV and then saved which converts it into a RGB image. Also BGR tendency of cv2.imread is checked in this script. Remember that OpenCV imread reads the image in BGR order thus when we display it using matplotlib.pyplot.imshow we need to make a conversion of the image from *BGR2RGB*.

A color image in RGB is a 3 Layer 2-D Matrix represented as ![equation1](http://www.sciweavers.org/tex2img.php?eq=M%20%20%5Ctimes%20N%20%5Ctimes%20%20%203&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0), where *M* and *N* are the width and height of the image respectively. A gray image is of the type:  ![equation2](http://www.sciweavers.org/tex2img.php?eq=M%20%20%5Ctimes%20N%20%5Ctimes%20%20%201&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0).
