# Game: Rock, Paper, Scissors
In this project you will make a Rock, Paper, Scissors game and play against the computer. The winner is decided by these rules:

* Rock blunts scissors
* Paper covers rock
* Scissors cut paper

- First, let the player choose Rock, Paper or Scissors by typing the letter ‘r’, ‘p’ or ‘s’;
- Then computers turn;
- Decide game win, lose or draw, print choice of both sides

1. Use python to implement the game play
2. Write unit tests with pytest
"Pytest is a mature full-featured Python testing tool that helps you write better programs" - https://docs.pytest.org/en/latest/
3. Create a Dockerfile that allows us to build a docker container and execute the tool with docker run without having any dependencies other than docker installed
- docker run -it <container-build> pytest -v  should execute the unit tests
- docker run -it <container-build>  should execute the app
4. Add at least one unit test to simulate what would happen if github returns 500
