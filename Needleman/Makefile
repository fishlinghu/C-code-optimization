# C compiler
CC = g++
CC_FLAGS = -O2 -m32

needle: 
	$(CC) $(CC_FLAGS) needle.cpp -o needle -lrt
temp:
	$(CC) $(CC_FLAGS) needle_temp.cpp -o needle_temp -lrt 
v2:
	$(CC) $(CC_FLAGS) needle_v2.cpp -o needle_v2 -lrt 
v3:
	$(CC) $(CC_FLAGS) needle_v3.cpp -o needle_v3 -lrt
cuda:
	nvcc needle_CUDA.cu -o needle_CUDA
pthread:
	$(CC) $(CC_FLAGS) needle_pthread.cpp -lpthread -o needle_pthread -lrt
clean:
	rm -f needle result.txt 
