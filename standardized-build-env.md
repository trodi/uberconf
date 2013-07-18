standardized build environment
==============================
enterprises have more to gain due to scale than start ups
need to be ambitious about automation
rigid conventions inhibit innovation and efficiency, idea of _degrading conventions_ is everywhere
* extend
* replace

gradle like ant, (a collection of tools, not a _framework_), but adds ability to plugin etc.
can force that a particular dependency sneaks in or force a particular standard task always exists
maxParallelForks - set num of cores to run

init scripts
------------
facilitate cross platform config
can have init script for gradle intall (or individual config, think dot files)
can specify plugins (don't have to specify at each build.gradle)
=don't want to impl our plugins here, just wire up

wrapper
-------
create wrapper gradle that gets checked into source control, will bootstrap install of gradle etc for you *auto*
will pin build to a version of gradle (there's a good vid). can provide custom distribution with your own init
scripts.
> self bootstrapping build system