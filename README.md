# Indices 0.6d

## Summary:

This is a program to display information about the indices that the BFS filesystem maintains.  It currently displays a list of the Indices present on all mounted volumes (along with type, size, modtime and creation time). However, this is a moderately early release and more are planned.

## Caution:

* THIS IS A DEVELOPMENT VERSION. It is features incomplete. *

## About BFS Indices:

BFS has the capability to create an index on any attribute, which can then be used for fast lookups of files that have that attribute. However, the system doesn't provide an interface to its indices for the end user. Therefore, this program.

To learn more about attributes, read the BeOS user docs. 
To learn more about BFS, read Dominic Giampaolo's excellent book _Practical file system design with the Be file system_.

## License:

Indices is distributed under the GPL, and therefore source is included in the archive.

The next step is to add index management, such as adding and deleting indices as well as finding attributes present previous to an index being created.

## ChangeLog:

0.6d:
Volumes with no indices are not displayed.
New Volumes menu in the volumes window.
