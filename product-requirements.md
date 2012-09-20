Requirements for Scientific Runner
----------------------------------

x Runs balanced over multiple machines if no automatic cluster available
o Centralized database over all parameters and applications to run
o Simple generation of new runs based on presets
x Parameters should be set specifically or by ranges
x Resulting data from runs should be stored in the database or to file / folder
o Runs should have possiblity to be dependent on each other
x Make it possible to set off groups of runs by easy selection (or by triggers such as version updates of software)
x Make it possible to set off runs when new data is available from other runs
o Cache results based on parameter combination and software version
x Tag all data from each run with an unique ID that can be used to look up and compare data at a later time, also useful to see variations between versions of the software in use
x Create a nice GUI that allows easy access to results by parameter selection

Possible extensions
-------------------

Check possibility to use LazyRunner or reuse code from there.
