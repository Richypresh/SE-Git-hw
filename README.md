\# SE-Git-hw



This is my repo for the Git/GitHub homework assignment. Honestly, going in I barely knew what to do, so this was mostly me learning as I went. It covers making a repo, branching, pull requests, fixing a merge conflict on purpose, and using issues.



\## Files



\- `hello\_world.py` - prints `Hello, World!`

\- `apple.py` - prints `I eat apple`, added on a separate branch called `feature-1`

\- `README.md` - this file



\## How to Run



```bash

python hello\_world.py

python apple.py

```



\## What I Did



I made the repo, cloned it to my computer, and pushed my first commit with `hello\_world.py`. Then I made a new branch called `feature-1`, added `apple.py` on it, and pushed that branch separately. After that, I opened a pull request to merge `feature-1` into `main` and merged it once it was reviewed.



\## The Merge Conflict (this part took me a while)



I had to intentionally create a merge conflict to see how to fix one. I changed the same line in `hello\_world.py` on two different branches, and when I tried to merge them Git stopped me with:

At first I honestly didn't know what I was looking at - the file had these weird lines in it:

Once I understood that everything between `<<<<<<<` and `=======` was one version and everything between `=======` and `>>>>>>>` was the other version, it made a lot more sense. I picked the line I wanted to keep, deleted all three marker lines, saved the file, then ran:



```bash

git add hello\_world.py

git commit -m "Resolve merge conflict in hello\_world.py"

```



and that fixed it. That was probably the part of this assignment that confused me the most, but once I actually saw a real conflict and worked through it, it clicked.



\## Issues \& Resolutions



| Issue | Assigned To | Description | Resolution | Status |

|---|---|---|---|---|

| #2 | me | Review the Hello World program and verify that the program runs correctly and follows the assignment requirements. | Ran `python hello\_world.py`, confirmed it printed "Hello, World!" as required, and confirmed the code matched the assignment requirements | Closed |

| #3 | classmate | Review apple.py and verify that the program prints the required message and is properly committed to the feature branch. | Confirmed apple.py prints "I eat apple" and that it was committed to the feature-1 branch | Closed |



\## Author



Precious Uwakwe

