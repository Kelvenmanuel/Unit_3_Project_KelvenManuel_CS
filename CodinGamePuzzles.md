③Solve the puzzles below using Python3 as the programming language. Once you pass all the test cases. 
Copy your code and uploaded to your GitHub, inside a file called CodinGamePuzzles.md, with comments about your experience.

I. Onboarding Puzzle
```.py
# game loop
while 1:
    enemy_1 = input()  # name of enemy 1
    dist_1 = int(input())  # distance to enemy 1
    enemy_2 = input()  # name of enemy 2
    dist_2 = int(input())  # distance to enemy 2

    # Write an action using print

    # Enter the code here
    
    if dist_1 < dist_2:
        print(enemy_1)
    else:
        print(enemy_2)

```


II. The Descent
```.py
import sys
import math

# The while loop represents the game.
# Each iteration represents a turn of the game
# where you are given inputs (the heights of the mountains)
# and where you have to print an output (the index of the mountain to fire on)
# The inputs you are given are automatically updated according to your last actions.


# game loop
while True:
    mountain = []
    for i in range(8):
         # represents the height of one mountain.
        mountain.append(int(input()))
    
    kill_mountain = max(mountain)
    index_mountain = mountain.index(kill_mountain)
    print(str(index_mountain))
        
    # Write an action using print
    # To debug: print("Debug messages...", file=sys.stderr)

    # The index of the mountain to fire on.

```

III. Power of Thor Episode 1
Extra for HL and motivated SL:
iV. There is no spoon - Episode 1


Comments: 

At the begin I quite did not get the purpose of the exercise and I did not understant how to code specifically. But I talked with alex and he explain me what I have to do and them I could code, is missing one code that I am kind of confuse but I will do more research about python coding and I expect to be done with it in the next few days. 
