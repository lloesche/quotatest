# quotatest
Container to test container quotas

Simple container that upon start writes a file of `$SIZE` in MB size (default: 1024MB) to `$OUTFILE` (default: /testfile).
When it's done it'll block forever / until interrupted.

I use this container to test different container quota systems (e.g. Docker, Mesos UCR, ...) on a variety of filesystems.
