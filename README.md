# final-for-Coding-II

my project is a Tic-Tac-Toe winner prediction program built with Python and PyTorch.
The purpose of this project is to train a simple neural network to look at a Tic-Tac-Toe board and predict whether X is likely to win, or whether O might win or the game might end in a draw.
The program starts by loading a Tic-Tac-Toe dataset from the UCI Machine Learning Repository. Each board space is converted into a number: X becomes 1, O becomes -1, and a blank space becomes 0. The result is also converted into numbers so the model can learn from it.
The main feature of this project is the neural network. It has 9 input values, one for each space on the board. Then it passes through two hidden layers before making a final prediction. The output tells us which result the model thinks is more likely.
Now I’ll demonstrate the program.
When the program runs, it first trains the model. After training, it asks the user to type in 9 characters for the board. The user can type x for X, o for O, and b for blank spaces.
For example, I can enter:
x b o b x b o b x
The program then prints the board like this:
x | b | o
b | x | b
o | b | x
Then it sends that board into the trained model and prints a prediction.
For this example, the output might be:
Prediction: X will probably win.
Another example input could be:
o o b x x b b b b
This represents a board where O has two spaces in the top row, and X has two spaces in the middle row. The program will analyze the board and predict the most likely result based on what it learned from the training data.
Some key features of this program are that it uses real training data, converts Tic-Tac-Toe boards into numbers, trains a PyTorch neural network, accepts custom user input, displays the board clearly, and gives a simple prediction.
Overall, this project shows how machine learning can be used to recognize patterns in a game board and make predictions based on examples it has already learned from.

Video link:
https://drive.google.com/file/d/1cXpNNK1qQ7CXm4ZMuswXhnqnVU8Tpb0L/view?usp=sharing
