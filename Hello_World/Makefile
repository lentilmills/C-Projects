.PHONY: all re clean fclean

NAME = hello

SRC =	*.c

INC = 	*.h

FLAGS = -Wall -Wextra -Werror

all: $(NAME)

$(NAME):
	gcc $(FLAGS) $(SRC) -I $(INC) -o $(NAME)

fclean: clean
	rm -rf $(NAME)

re: fclean all