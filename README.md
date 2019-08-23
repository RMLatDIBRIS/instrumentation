# instrumentation

We provide an instrumentation layer for Node.js based on [Jalangi2](https://github.com/Samsung/jalangi2/), a dynamic analysis framework based on code instrumentation.

To run the instrumentation engine you need Node.js installed as well as its package manager, [npm](https://www.npmjs.com/). To install the required libraries `cd` into `nodejs` and type:

    $ npm install

To run a program with the instrumentation use the convenient Bash script:

    $ ./instrument.sh trace.txt program.js [program-args ...]

The text file will contain the execution trace.
