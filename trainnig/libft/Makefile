NAME  = libft.a
CC	= gcc
CFLAG = -Wall -Werro -Wextra
RM = rm -fr

SRCS = ft_isalpha.c
OBJS = $(SRCSB:.c=.o)

SRCSB =
OBJSB = $(SRCSB:.c=.o)




all = $(NAME)

$(NAME) : $(OBJS) $(OBJSB)
	ar -rcs $(NAME) $^

%.o : %.c
	$(CC) $(CFLAG) -o $@ -c s^

clean :
	$(RM) $(OBJS)

flcean : clean
	$(RM) $(NAME)

re : fclean all

bonus : $(OBJSB)
	ar -rcs $(NAME) $(OBJSB)
