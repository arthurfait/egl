TARGET=sample
LIBS = `pkg-config --libs egl glesv2 x11`
CFLAGS = `pkg-config --cflags egl glesv2 x11`
CXX = g++ -O3 

CPU_SOURCES=sample.cpp


all:
	$(CXX)  $(CFLAGS)  $(LIBS) -o $(TARGET) $(CPU_SOURCES)
	strip $(TARGET)
clean:
	rm -f ./*.o $(TARGET) 

