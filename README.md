# QuizzGame

The project consists of a multithreaded server that accepts any number of clients. Each client receives a question that they have to answer correctly in a specific amount of time to receive points. Also, all players are synchronized and can only go to the next question when all other players have answered the current one. The server performs all the logic, while clients only answer questions. Also, the server manages the situation when one or more players leave the game so it can continue normally.

The project was implemented using C++, C, and the POSIX API for threads and network communication. Also, the questions and answers are stored in a SQLite database.
