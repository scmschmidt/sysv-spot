# sysv-spot

This script spots SysV init scripts in a (SUSE) system to help prepare for a time, when 
init scripts are not supported anymore (SLE 16) and stop working.

It lists for each script found in `/etc/init.d`:

- the name of the script,
- the RPM package (if available),
- the origin (either the RPM package vendor or an entry of an internal list) and
- how to handle the finding.

## Requirements

The script requires Python 3.6, which is available on SLE 12 SP5 and later.


## Usage

Clone the repo or simply download `sysv-spot`, make it executable und execute it.
Administrative privileges might be necessary, depending on the permissions set for the init scripts.




