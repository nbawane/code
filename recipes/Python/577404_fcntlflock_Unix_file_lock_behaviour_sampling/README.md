###fcntl.flock() (Unix file lock) behaviour sampling script

Originally published: 2010-09-22 00:08:15
Last updated: 2010-09-22 00:11:12
Author: Jan Kaliszewski

A quick *fcntl.flock(fcntl.LOCK_EX | fcntl.LOCK_NB)* call sampling script: with *one file object* (and descriptor) or *separate file objects* (and different descriptors) pointing to the same filesystem path -- with/without **threading** or **forking**.