\# Git Bisect Investigation



\## What Git Bisect does



Git Bisect uses binary search to find the commit that introduced a bug.



\## Why binary search is useful



Instead of checking every commit one by one, Git checks commits in the middle of the history. This reduces the number of commits that need to be tested.



\## Investigation



Known good commit:



`fb8d8db` - feat: add bisect demo baseline



Known bad commit:



`1729733` - feat: add later bisect change



The test checked whether `src/bisect-demo.txt` contained the text `BUG`.



\## Result



Git identified:



`9acb4e0` - feat: introduce deliberate bug



as the first bad commit.



\## Verification



The bug was introduced when `src/bisect-demo.txt` was changed to contain `BUG`.

