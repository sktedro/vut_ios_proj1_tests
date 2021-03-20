Author: Tedro

No rights reserved

NOTE: Probably won't work on Windows OS!

TESTING INSTRUCTIONS:

[kit] can be:
  - 'orig' for test cases or reference outputs copied from the assignment
  - [name] for test cases or reference outputs written by a user [name]

To run tests from a kit and compare your outputs to reference outputs, run

./run [kit]
  - eg. ./run orig
  - or  ./run tedro

You can check what users have written tests and reference outputs by checking 
in the data/input folder

To compare reference output and your output (which has already been generated),
it is enough to run ./compare [kit]

INSTRUCTIONS TO GENERATE REFERENCE OUTPUTS (to improve these tests):

To generate reference output from your tradelog file using your test cases,
put tradelog in the main folder and run 
  - ./generateRef [kit] (while [kit] is your nickname)

which will run your tradelog with data/input/[kit] and save the reference
output into data/ref/[kit]


If you want to write your own test cases, please only write one test with
stock-4.log.gz in a single file. The testing seemed unstable with removing and
copying all logs for every single test case
