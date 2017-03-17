# Programming Project - Unit 1,1
*by Igor A. Brandão -> 2014041985*

**Goals**
- Reinforce and practice main ideas and skills presented in the first
lessons about Python;
    - Loop, random, numpy, list, functions, so on...

**IMD Bet Game**

In the IMD bet game, your next move depends on the number of eyes you throw with the dice.

**Rules**

*Input:*
- Floor "f", where step = max(0,f);
- Epoch (roll) = 100;
- Seed;
- Number of rounds = **500**.

*For each rounds*

*For each epoch (roll):*

- Roll the dice;
- Determine the next step;

| Case | Whats happen |
| --- | --- |
| `Case 1,2:` | Decrease step by one |
| `Case 3,4,5:` | Increase step by one |
| `Case 6:` | Roll de dice again and move accordling to result of the new dice |

- There is a 0,1% probability that assign the step to 0 (zero) in each step;
- Store the current step

Round[i] = steps