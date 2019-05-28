##
## EPITECH PROJECT, 2018
##
## File description:
## Makefile
##

NAME	=	generator

SRC		=	src/check_input.c			\
			src/algo_perfect.c			\
			src/display_free_tab.c		\
			src/find_maze.c				\
			src/perfect_maze.c			\
			src/imperfect_maze.c		\
			src/check_place.c			\
			src/check_direction.c		\
			src/strange_maze.c			\
			main.c

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


.PHONY:		all clean fclean re
