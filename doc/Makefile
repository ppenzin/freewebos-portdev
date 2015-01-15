CC=dot
#CC=neato

dependency_graph: graph.png

graph.png: graph.dot
	$(CC) -Tpng $? -o $@

clean:
	rm -f *.png
