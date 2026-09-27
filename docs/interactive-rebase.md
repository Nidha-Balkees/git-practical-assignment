\# Interactive Rebase Demonstration



\## Purpose



Interactive rebase was used to clean up the commit history of the `feature/interactive-rebase` branch.



\## Initial History



The branch initially contained four small commits:



\- feat: add user module

\- feat: add payment module

\- feat: add notification module

\- fix: improve application modules



\## Rebase



The following command was used:



git rebase -i HEAD\~4



The four commits were reorganized and squashed into two meaningful commits.



\## Final History



The final history contains two feature commits instead of four small commits.



Interactive rebase helps make commit history cleaner and easier to understand before sharing a feature branch.



\## Important Note



Interactive rebase rewrites commit history, so it should be used carefully on branches that have not already been shared with other developers.

