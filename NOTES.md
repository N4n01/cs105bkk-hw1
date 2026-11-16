# HW1 notes

Answer each question in a few sentences. Be specific: name the function, the error or the command.

## What did you try?
I begin by going through each function in delivery.py, figuring out what it was supposed to do. Then I implemented them one by one and used pytest to check if everrything worked. Checked the GitHub repository information page to understand what is going on.
## What broke, and how did you fix it?
Initially, the unfinished functions raised NotImplementedError as it was left to be completed. I replaced them with the actual code and handle things like invalid prices using ValueError. I also used .copy() to avoid accidentally sharing lists. I also messed up selecting the right object to return in my first few tries.
## What would you do differently next time?
Next time, I should probably test each function more frequently while writing the code instead of running the tests after I'm done with a few tasks. It would be a more efficient workflow. I should also pay more attention to special cases like empty lists and boundary values from the start. I also start out accidently returning False instead of NotImplemented for __eq__ but quickly correct it.