all: run
run: run.cpp
	nvcc -O2 run.cpp ../objs/Graph.o ../objs/IO.o ../objs/Match.o ../objs/Util.o -o run
exec:
	./run ../data/sample_data.g ../data/sample_query.g
clean:
	rm -f run
