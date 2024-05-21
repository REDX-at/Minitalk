CC = cc
CFLAGS = -Wall -Wextra -Werror
BONUS_NAME = Minitalk_Bonus

$(BONUS_NAME): make_tools server_bonus client_bonus
	@echo "Building $(BONUS_NAME)"

make_tools:
	@echo "Building Tools "
	@cd ./Tools && make > /dev/null

client_bonus: client_bonus.c make_tools
	@echo "Compiling client_bonus.c √"
	@$(CC) $(CFLAGS) client_bonus.c ./Tools/libtools.a -o client_bonus

server_bonus: server_bonus.c make_tools
	@echo "Compiling server_bonus.c √"
	@$(CC) $(CFLAGS) server_bonus.c ./Tools/libtools.a -o server_bonus

all: $(BONUS_NAME)

clean:
	@echo "Cleaning √"
	@rm -f server client client_bonus server_bonus
	@cd ./Tools && make fclean > /dev/null

fclean: clean 

re: fclean all

.PHONY: clean
