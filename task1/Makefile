CXX = g++
CXXFLAGS = -std=c++20 -pthread -Wall -Wextra -O2
TARGET = main
SRC = main.cpp

.PHONY: all run clean

all: $(TARGET)

$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC)

run: $(TARGET)
	./$(TARGET)

clean:
	rm -f $(TARGET)