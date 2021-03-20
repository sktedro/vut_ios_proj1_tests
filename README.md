Author: Tedro
No rights reserved

Probably won't work on Windows OS!

INSTRUCTIONS:

[kit] can be:
'orig' for test cases or reference outputs copied from the assignment
[name] for test cases or reference outputs written by a user [name]

To run tests from a kit and compare your outputs to reference outputs, run
-./run [kit]
  -eg. ./run orig
  -or  ./run tedro

You can check what users have provided reference outputs by checking in the
data/input folder



To generate reference output from your tradelog file using your test cases,
put tradelog in the main folder and run (while [kit] is your nickname)

./generateRef [kit]

which will run your tradelog with data/input/[kit] and save the reference
output into data/ref/[kit]


To compare reference output and your output (which has already been generated),
it is enough to run ./compare [kit]
