banned
======

Eggdrop script for banning IPs in iptables

1. Place the banned folder under <eggdrop path>/scripts
2. Load the scripts/banned/banned.tcl in your eggdrop.conf.
2. Edit channels variable at top of banned.tcl to specify channels
   where commands can be run.
3. Ensure that user the eggdrop is run as has sudo access to run 
   <eggdrop path>/scripts/iptables.sh no password prompt.
