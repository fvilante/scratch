
BUILD_DIR=.
TARGET_NAME=learn_opengl
GLAD_LIB_FLAGS=glad/src/glad.c -I./glad/include
LIBS=-lglfw -ldl

all: build run

build:
	 g++ -o $(BUILD_DIR)/$(TARGET_NAME) test.c $(GLAD_LIB_FLAGS)  $(LIBS)

run: 
	$(BUILD_DIR)/$(TARGET_NAME)

clean:
	rm -f $(BUILD_DIR)/$(TARGET_NAME)