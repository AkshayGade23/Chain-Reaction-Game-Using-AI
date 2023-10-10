First approach of evaluation function -
    In this strategy, the AI bot will look at all possible moves and select the move that maximizes its chances of winning in the next move. Here's a modified version of your code with the AI bot using this strategy.This code provides a simple heuristic-based AI strategy for the AI bot. It evaluates each possible move by the AI bot and selects the move that maximizes its chances of winning based on the current board state.
    


Second approach of evaluation function -

    In this evaluation function, we consider several factors:

        - The number of squares owned by the AI player (playerScore).
        - The number of squares owned by the opponent (opponentScore).
        - The potential score increase for the AI player and the opponent based on potential future moves (playerPotentialScore    and opponentPotentialScore).

        The function then calculates a final score that takes into account the current state of the board and the potential future moves. The AI bot will try to make moves that maximize its final score.