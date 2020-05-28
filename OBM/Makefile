HEADERS =-I./ -I/usr/include/ -I/usr/include/boost/include -I/usr/include/gdal/
LIBS =-L./ -L/usr/lib -L/usr/lib


facilityAccesscount:  facilityaccesscount.cpp
	mpicxx $(HEADERS) $(LIBS) -std=c++11 -fopenmp -Wall -O3 -o facilityAccesscount facilityaccesscount.cpp -lgdal -lmpi
clean:
	rm  facilityAccesscount
