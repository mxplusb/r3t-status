---
section: issue
title: vSAN is broken
date: 2020-01-14T05:30:00.000Z
resolved: true
resolvedWhen: 2020-01-16T22:45:00.000Z
affected:
  - vSAN
  - Ghost
  - Harbor
  - Git
  - Network Controller
severity: down
---
### Cause

vSAN won't reconfigure properly, so everything is running off the two emergency disks and shit is real broken, basically just vCenter and DNS are the only things online while I figure out wtf is wrong with it.

### Update

Well, there's no pretty much about it, shit's broken yo. So it turns out that I'm like...15 months behind on vSphere patches. Who knew, right? So I'm basically patching the fuck outta these hosts, trying to get all the versions in sync with my witness host, then I'm gonna try and re-enable vSAN and see what happens. If I can make it, it's late and I'm tired, lol. Maybe in the morning.

### Update

Okay, so I think the core problem has been fixed because there were a ridiculous amount of updates to be had on all sources, so I think we're all good. Things are migrating back and stuff should be turning back on here soon!

### All done!
