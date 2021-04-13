# Four_In_A_Row_AI

![image](https://user-images.githubusercontent.com/55422467/114603808-fa784180-9cb9-11eb-8f61-e327a861d38a.png)

# Introduction
The problem has been solved using Python Language with the comprehensive implementation of Min-Max Alpha-Beta Pruning Algorithm. The Depth of the search for the algorithm has been customized for a quicker but less accurate response from an AI agent.. Main Functions have been highlighted as below:
1.	Priority for Winning/ Blocking the Opponents
2.	Min Max Algorithm
3.	Winning Combinations

# Winning Combinations
There are four winning (vertical, horizontal, positive sloped and negative sloped) combinations in this game which has been implemented correctly in this task using the winning_move () Function which has been shown in figure 1. 

![image](https://user-images.githubusercontent.com/55422467/114604052-4c20cc00-9cba-11eb-96d8-4b940b05a7c5.png)

Figure 1: winning_move function

# Priority for Winning/ Blocking the Opponents
Prioritization of moving the pieces according to the situation has been done by the following 3 cases
Case 1: Own 3 pieces are in position. Next move will win it for myself. (Priority-1)
Case 2: Opponents 3 pieces are in position. Block it. (Priority-2)
Case 3: Own 2 Pieces are in position. Build it for Getting Case 1. (Priority-3)
These 3 cases has been implemented using the combination of pick_best_move (), score_position () and evaluate_window () functions as shown respectively in figure 2, 3, 4.








![image](https://user-images.githubusercontent.com/55422467/114604076-52af4380-9cba-11eb-9624-68668e92e4fa.png)

Figure 2: pick_best_move function















![image](https://user-images.githubusercontent.com/55422467/114604092-580c8e00-9cba-11eb-83d3-68e4096c1e10.png)


Figure 3: score_position () function







![image](https://user-images.githubusercontent.com/55422467/114604115-5c38ab80-9cba-11eb-8f3c-2c2a732c7485.png)


Figure 4: evaluate_window function

# Min-Max Algorithm (Alpha-Beta Pruning)
Classic Min-Max algorithm with Alpha Beta pruning has been implemented as minimax () function in this task. Depth has been set at maximum 5 called from main function which has caused the AI agent to react faster sacrificing a bit of accuracy which has been shown in figure 5.

![image](https://user-images.githubusercontent.com/55422467/114604145-65297d00-9cba-11eb-9da9-4693b959071c.png)

Figure 5: minimax () function

# Conclusion:
The Task has been clinically completed with the successful implementation of Min-Max algorithm with Alpha Beta pruning. Additionally the depth of the searching has been customized (Bonus-1). However, there are rooms of improvement in case of accuracy and UI development of this game can be a future prospect of this task.
