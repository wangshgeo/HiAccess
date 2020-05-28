HEADERS =-I./ -I/usr/include/ -I/usr/include/boost/include -I/usr/include/gdal/
LIBS =-L./ -L/usr/lib -L/usr/lib


facilityAccess:  facilityaccess.cpp
	mpicxx $(HEADERS) $(LIBS) -std=c++11 -fopenmp -Wall -O3 -o facilityAccess facilityaccess.cpp -lgdal -lmpi
clean:
	rm  facilityAccess
