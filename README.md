cmake -D OPENCV_EXTRA_MODULES_PATH=./../opencv_contrib-3.4.1/modules/ ..

cmake -DENABLE_PRECOMPILED_HEADERS=OFF -D CMAKE_BUILD_TYPE=Release -DBUILD_TIFF=ON -D CMAKE_INSTALL_PREFIX=/usr/local -D OPENCV_EXTRA_MODULES_PATH=/home/airobot/opencv-3.4.3/opencv_contrib-3.4.3/modules/ ..
## OpenCV: Open Source Computer Vision Library

### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org/master/>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <https://github.com/opencv/opencv/issues>

### Contributing

Please read the [contribution guidelines](https://github.com/opencv/opencv/wiki/How_to_contribute) before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the [coding style guide](https://github.com/opencv/opencv/wiki/Coding_Style_Guide).
