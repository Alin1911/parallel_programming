build:
	@echo "Building..."
	@gcc -o tema1_par tema1_par.c genetic_algorithm.c -lm -Wall -Werror -lpthread
	@echo "Done"

build_debug:
	@echo "Building debug..."
	@gcc -o tema1_par tema1_par.c genetic_algorithm.c -lm -Wall -Werror -lpthread -O0 -g3 -DDEBUG
	@echo "Done"

clean:
	@echo "Cleaning..."
	@rm -rf tema1_par
	@echo "Done"
