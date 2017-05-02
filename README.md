# Mastering OpenCV 3 - Second Edition
This is the code repository for [Mastering OpenCV 3 - Second Edition](https://www.packtpub.com/application-development/mastering-opencv-3-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786467171), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will put you straight to work in creating powerful and unique computer vision applications. Each chapter is structured around a central project and deep dives into an important aspect of OpenCV such as facial recognition, image target tracking, making augmented reality applications, the 3D visualization framework, and machine learning. You’ll learn how to make AI that can remember and use neural networks to help your applications learn.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

Each chapter of the book is for a separate project. Therefore there are 7 projects for the 7 chapters (note that the 1st edition of the book also had a 9th chapter, only in the eBook).

You can run each project separately, they each contain a README.md text file describing how to build that project, using CMake in most cases, because CMake can be used with many compilers and many operating systems.

To build & run the projects for the book:
* Install OpenCV (version 3.1.0 is recommended, whereas OpenCV 2 is only supported in the 1st edition of this book). eg: go to "http://opencv.org/", click on Downloads, download the latest OpenCV 3.1 version (including prebuilt library), and extract it to "C:\OpenCV" for Windows or "~/OpenCV" for Linux. In OpenCV v3.1.0, the prebuilt OpenCV library is in "C:\OpenCV\build" or "~/OpenCV/build", such as "C:\OpenCV\build\x64\vc9" for MS Visual Studio 2008 (or "vs10" folder for MS Visual Studio 2010, or the "x86" parent folder for 32-bit Windows).
* Install all the source code of the book. eg: extract the code to "C:\MasteringOpenCV" for Windows or "~/MasteringOpenCV" for Linux.
* Install CMake v2.8 or later from "http://www.cmake.org/".

The code will look like the following:
```
int cameraNumber = 0;
if (argc> 1)
  cameraNumber = atoi(argv[1]);
  // Get access to the camera.
cv::VideoCapture capture
```

you will also need a computer, and IDE of your choice (such as Visual Studio, XCode, Eclipse, or QtCreator, running on Windows, Mac, or Linux). Some chapters have further requirements, in particular:

* To develop an OpenCV program for Raspberry Pi, you will need the Raspberry Pi device, its tools, and basic Raspberry Pi development experience.
* Several desktop projects require a webcam connected to your computer. Any common USB webcam should suffice, but a webcam of at least 1 megapixel may be desirable.
* CMake is used in some projects, including OpenCV itself, to build across operating systems and compilers. A basic understanding of build systems is required, and knowledge of cross-platform building is recommended.

An understanding of linear algebra is expected, such as basic vector and matrix operations, and eigen decomposition.

## Related Products
* [OpenCV 3 by Example [Video]](https://www.packtpub.com/application-development/opencv-3-example-video?utm_source=github&utm_medium=repository&utm_campaign=9781787287259)

* [Learning OpenCV 3 Application Development](https://www.packtpub.com/application-development/learning-opencv-3-application-development?utm_source=github&utm_medium=repository&utm_campaign=9781784391454)

* [Learning OpenCV 3 Computer Vision with Python - Second Edition](https://www.packtpub.com/application-development/learning-opencv-3-computer-vision-python-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785283840)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
