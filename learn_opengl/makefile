
BUILD_DIR=./build
TARGET_NAME=learn_opengl
TARGET=$(BUILD_DIR)/$(TARGET_NAME)
GLAD_LIB_FLAGS=glad/src/glad.c -I./glad/include
LIBS=-lglfw -ldl


.PHONY: all build clean run

all: build run

build: $(TARGET)

$(TARGET): test.c
	 g++ -o $(TARGET) test.c $(GLAD_LIB_FLAGS)  $(LIBS)

run: 
	./$(BUILD_DIR)/$(TARGET_NAME)

clean:
	rm -f $(TARGET)