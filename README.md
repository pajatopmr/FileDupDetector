# FileDupDetector
Detect Mac OS X duplicate files caused by Google Drive and file duplicate file downloads.

Over a long span, Mac OS X will generate many duplicate files either due to the User, for example, recreating file
duplication by accident during downloads or due to applications, for example Google Drive, inadvertently creating duplicates.

In many cases these are merely annoying.  In some cases they are downright troublesome causing build errors.  So the need to
detect and fix duplicated files arises.  Typically, advanced Users will create scripts to detect duplicate files and act on
them accordingly.  More often though, the process is a tedious manual one of responding to a system complaint by removing
duplicates or renaming files accordingly.

This project is an attempt to build up a suite of functions within a tool to deal with the detection and processing of files
duplicated in some fashion.  The most fundamental behavior is to detect similarly named files or directories with identical
sizes, usually with the string " (#)" embedded in the file, where # can be 1 or higher.
