Clone of kafka-tools
===========

This repository is clone of `linkedin/kafka-tools`.  There are no
functional changes, this is purely here to provide a vendored version
of the tools.

This is being done because the release of kafka-tools in pypi is
lagging the master branch in github, and we need some of those
features for our use, specifically rack-aware placement.

The intended use of this is to tag this repo with the date
(e.g. 20170705), and use that date tag to build from.

Don't start the tag with a letter.  Dpkg/apt gets upset about that.
