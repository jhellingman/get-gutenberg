== get-gutenberg ==

This project contains a number of Perl/.sh/.bat scripts to download the complete
set of Project Gutenberg public domain ebooks to your computer (using rsync).

To save bandwidth and disk-space, only the non-derived files, in their
compressed (.zip archive) form are downloaded.

Note that currently, this set of ebooks is over 100 gigabytes, and thus will
take considerable time to download. The scripts are written such that you
can stop them, and restart them at a later time. This way, you can also update
the collection after new books have been posted.

Another script will convert all .zip files to .7z compressed archives, which
saves about 6% on the total size. Again, the convertion can be re-run
to update the re-compressed collection.

== Future plans ==

Add code to turn chunks of this collection (of, lets say, 1000 books) into
torrents, and seed them.
