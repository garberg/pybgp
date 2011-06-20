Github copy notes
-----------------

This is my github copy of pybgp, which is usually hosted on launchpad. Although
I have little towards bzr, I am mort comfortable with git and I really like
github so I thought I'd make a copy here for my own convenience. Please note
that at this point, this version is not modified from the original with
exception to this readme file.


Original README
---------------

This code is a simple python BGP implementation. It only speaks the protocol;
there is no code for building or maintaining a RIB, or doing kernel-layer
stuff such as inserting or deleting routes.

Whilst I'm not opposed to someone else adding those things, I have no use
for them, so please don't ask me to write them ;o)

The intended use is for things such as anycast load-balancing, as with DNS
or similar services. There is a script in "examples" which is very similar
to the code we use.

There are a few tests; there could and should be more.

The code as written requires Python 2.5 struct.unpack_from. It would be pretty
easy to either remove this requirement or make a compatibility layer for older
python versions.



The project is run, somewhat against my better judgement, in Launchpad:

 https://launchpad.net/pybgp
