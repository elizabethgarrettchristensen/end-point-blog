---
author: Selena Deckelmann
gh_issue_number: 59
tags: conference, performance
title: 'Fun with 72GB disks: Filesystem performance testing'
---

If you haven't heard, the [Linux Plumbers Conference](http://linuxplumbersconf.org/) is happening September 17-19, 2008 in Portland, OR. It's a gathering designed to attract Linux developers - kernel hackers, tool developers and problem solvers.

I knew a couple people from the Portland PostgreSQL User Group ([PDXPUG](http://pugs.postgresql.org/pdx)) interested in pitching an idea for a talk on filesystem performance. We wanted to examine performance conventional wisdom and put it to the test on some sweet new hardware, recently donated for performance testing [Postgres](http://www.postgresql.org/).

[Our talk](http://linuxplumbersconf.org/program/speakers/getspeaker.php?speaker=mwong.txt) was accepted, so the three of us have been furiously gathering data, and drawing interesting conclusions, ever since. We'll be sharing 6 different assumptions about filesystem performance, tested on five different filesystems, under five types of loads generated by [fio](http://git.kernel.dk/?p=fio.git;a=summary), a benchmarking tool designed by kernel hacker Jens Axboe to test I/O.

Look forward to seeing you there!
