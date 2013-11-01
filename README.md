submissionScriptCSC261
======================

A script in developement for formatting purposes


Usage This is specifically built for Grinnell CSC261 Artifical Intelligence.
I am generally absent-minded, so I tried stream-lining the submission process.

The process is detailed here:

http://www.cs.grinnell.edu/~weinman/courses/CSC261/2013F/assignments/index.html


input ex:

$script [doThis.scm withThis.scm] [doThis.c withThis.c]  justthis.scm

[ and ] pair denotes a driver with its sources preceding it

It is not necessary to use "[", but I include this for my own preference:
I want to be able to visually identify what drivers go with what sources.

If there is no driver for a source, it can be independent like justthis.scm

NOTES

This script has not been made to recognize files with different file extension, but the same name.
|
v
testfile.scm == testfile.c
You will get one output testfile.pdf
Depending on which came last, one will overwrite the other
