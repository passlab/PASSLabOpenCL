all: clean vecAdd_cl

.PHONY: checkEnv clean

vecAdd_cl: vecAdd.c
	gcc vecAdd.c -g -L/opt/intel/intel-opencl-1.2-5.0.0.43/opencl/lib64 -lm -lOpenCL -o vecAdd_cl
clean:
	rm -rf bin vecAdd_cl core
