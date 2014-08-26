edxbot
======

This is the configuration for the logbot that sits in the #edx-code IRC channel
on Freenode. It is designed to run on Heroku, and save IRC logs to an Amazon
S3 bucket.

You must set your AWS configuration via environment variables,
[as described in the `boto` documentation]
(http://boto.readthedocs.org/en/latest/boto_config_tut.html)
.
