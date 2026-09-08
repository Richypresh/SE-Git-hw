\# SE-Git-hw



A homework project demonstrating core Git and GitHub workflows: repositories, commits, branching, pull requests, merge conflict resolution, and issue tracking.



\## Project Description



This repository was built for a Software Engineering assignment covering the full Git/GitHub collaboration workflow. It contains two small Python programs and a documented history of branches, pull requests, a resolved merge conflict, and tracked issues.



\## Files



\- `hello\_world.py` — prints `Hello, World!`

\- `apple.py` — prints `I eat apple` (added on the `feature-1` branch)

\- `README.md` — this file



\## How to Run



```bash

python hello\_world.py

python apple.py

```



\## Workflow Summary



\- \*\*Branches:\*\* `main` (stable) and `feature-1` (added `apple.py`, merged via pull request).

\- \*\*Pull Request:\*\* `feature-1` → `main`, reviewed and merged. See the closed/merged PR in the \*\*Pull requests\*\* tab.

\- \*\*Merge Conflict:\*\* Simulated and resolved — see the "How I Resolved the Merge Conflict" section below.

\- \*\*Issues:\*\* Two issues were opened, assigned, worked on, and closed — see the "Issues \& Resolutions" section below.



\## How I Resolved the Merge Conflict



<!-- Replace this with your own details from Part 5. -->



While updating `hello\_world.py` on two different branches, both branches changed the same line of code in different ways. Running `git merge` produced a conflict:

I opened the file, found the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`), compared both versions, and manually edited the line to keep the version I wanted. I removed the conflict markers, saved the file, then ran:



```bash

git add hello\_world.py

git commit -m "Resolve merge conflict in hello\_world.py"

```



This completed the merge with no further errors.



\## Issues \& Resolutions



| Issue | Assigned To | Description | Resolution | Status |

|---|---|---|---|---|

| #1 | (you) | \*\[describe your issue]\* | \*\[what you did to fix it]\* | Closed |

| #2 | (classmate) | Review apple.py | Confirmed the script runs correctly | Closed |



\## Author



Precious Uwakwe

