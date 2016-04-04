# sidewinder
Python based system for monitoring changes on specific websites

In specific, you maintain a list of websites that may change.  You run the program and it checks those websites to see if they've changed since the last time you ran the program.  This is done with a hash on the website rather than storing the full text.  The date is also stored as an aside indicating how long it has been since it last changed.

Eventually, this might turn into a Broadsheet indicating what is 'new'.
