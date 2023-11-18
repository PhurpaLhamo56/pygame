# pygame
CSF101, CAP2
The detail OF the resources and elements used in the test case:

Test Initialization and Cleanup:

The setUp method initializes the Pygame module before each test.
The tearDown method cleans up the Pygame module after each test.
Test Case Methods:

test_bubble_collision: Tests whether a collision between two bubbles is detected correctly. It initializes a game, sets up two bubbles, launches a new bubble, simulates the game loop until the collision, and checks if the collision is recognized.
test_score_increment: Checks if the game increments the score correctly when bubbles are popped. It follows a similar procedure as the test_bubble_collision.
test_game_win: Tests the win condition of the game. It initializes a game with a winning board state, launches a bubble, simulates the game loop until the game ends, and checks if the win condition is recognized.
test_game_lose: Tests the lose condition of the game. It initializes a game with a losing board state, launches a bubble, simulates the game loop until the game ends, and checks if the lose condition is recognized.
test_arrow_rotation: Checks if the arrow's rotation is updated correctly based on user input (LEFT and RIGHT). It initializes a game, gets the initial angle of the arrow, simulates arrow rotations, and verifies the updated angle.
test_music_change: Verifies if the game changes background music during the game loop. It initializes a game, captures the initial music track, simulates the game loop until the music changes, and checks if the music track is different.
test_restart_game: Tests if the game state resets correctly after restarting. It initializes a game, simulates the game loop until a game over condition, captures the initial score and music track, triggers the end screen, and checks if the score is reset to zero and the music track changes.
