CC=g++-5
CFLAGS=-Wall -fexceptions -std=c++14 -O3 -fopenmp
BOAT_DIR=./../../
LIBS= -lboat -lpthread -lblas -lnlopt -lboost_serialization -lboost_system -lboost_coroutine

branin_hoo: branin_hoo.cpp
	$(CC) -o branin_hoo $(CFLAGS) -I$(BOAT_DIR)/include/ branin_hoo.cpp -L$(BOAT_DIR)/build $(LIBS) 

clean: 
	rm -f branin_hoo
