
# build helloworld executable when user executes "make"
helloworld: main.o
	$(CXX) $(LDFLAGS) main.o -o helloworld $(LIBS)
main.o: main.cpp
	$(CXX) $(CXXFLAGS) -c main.cpp

# remove object files and executable when user executes "make clean"
clean:
	rm *.o helloworld
    
    