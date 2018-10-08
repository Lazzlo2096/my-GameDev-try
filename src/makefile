.PTHONY: all clean

all: main

CFLAGS = -std=c++11
ALLEGRO_LIBS = -lallegro #-lallegro_primitives
ALLEGRO_LIBS_all2 = -lallegro -lallegro_primitives -lallegro_font -lallegro_ttf -lallegro_image -lallegro_dialog

headers = nachalo.h
cppers = main.cpp

main: $(cppers) $(headers)
	g++ $(cppers) $(ALLEGRO_LIBS) $(CFLAGS) -o main 
	#g++ -I ./ALX/include/ ./src/maPong.cpp ./src/Sprite.cpp ./src/PingPong.cpp ./src/Rectangle.cpp -lallegro -lallegro_primitives -lallegro_font -lallegro_ttf -std=c++11 -o maPong
	
clean:
	rm ./main