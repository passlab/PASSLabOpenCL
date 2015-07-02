# PASSLabOpenCL
Keep copy of OpenCL codes found from various places

To run OpenCL examples from NVIDIA CUDA SDK 4.2.9 on NVIDIA GPU on gpu.secs.oakland.edu,
follow the instruction from wiki (https://github.com/passlab/passlab.github.io/wiki, item 3 and 4 from Documents) to login 
to gpu.secs.oakland.edu and clone the repo. 

Then go to PASSLabOpenCL/NVIDIA_CUDA-OpenCL-4.2.9_Samples/OpenCL folder of the local copy of the repo. 
To launch make command will build all the examples and the binaries are coped to bin/linux/release/* folder. 
You should be able to see oclDeviceQuery, oclVectorAdd, oclMatrixMul, etc examples and run. 

The source files of each of the examples are in src folder, from where you can use make 
command to build it after you make changes to the source codes. 
