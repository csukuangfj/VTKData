VTK Data Directory
----------------------

This directory contains data and baseline images for VTK regression testing
and other VTK examples. (See
http://www.vtk.org/testing/TestingResults/Dashboard/MostRecentResults-Nightly/Dashboard.html
to see how regression testing is used.) Also see http://public.kitware.com/Dart
to learn about the Dart regression testing system.

The VTKData/Data directory are data files of various types. This includes
polygonal data, images, volumes, structured grids, rectilinear grids,
and multi-variate data.

The VTKData/Baseline are the testing images. These are used in testing to
compare a valid image against a generated image. If a difference between the
two images is found, then the test is considered to have failed.

-----

Refer to
https://www.vtk.org/Wiki/VTK_Datasets

```.sh
git clone git://vtk.org/VTKData.git VTKData
```

See also https://github.com/csukuangfj/VTKLargeData
