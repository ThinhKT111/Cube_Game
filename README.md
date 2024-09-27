How to run code:
1. g++ -c method.cpp -o method.o
2. g++ -c solve_edge.cpp -o solve_edge.o
3. g++ -c solve_concer.cpp -o solve_concer.o 
4. g++ -c type_cube.cpp -o type_cube.o
5. g++ main.cpp type_cube.o method.o solve_edge.o solve_concer.o -o main 
6. ./main