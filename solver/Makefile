##
## EPITECH PROJECT, 2018
##
## File description:
## Makefile
##

NAME	=	solver

SRC		=	main.c						\
			src/error_handling.c		\
			src/load_maze.c				\
			src/load_maze_two.c			\
			src/useful_fonctions.c		\
			src/start_astar.c			\
			src/initialize_list.c		\
			src/print_maze.c			\
			src/get_old_possibility.c	\
			src/check_case.c			\
			src/check_end.c

OBJ		=	$(SRC:.c=.o)

CCO		=	gcc -o

LIB		=	-L./lib -lmy

CFLAGS	+= -I./include/

RM		=	rm -rf

all:		$(NAME)

$(NAME):	$(OBJ)
			$(CCO) $(NAME) $(OBJ)

clean :
			$(RM) $(OBJ)

fclean:		clean
			$(RM) $(NAME)

re:			fclean all

.PHONY:		all clean fclean re
