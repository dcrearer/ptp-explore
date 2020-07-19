# ptp-explore

The repository contains a playbook that has tasks which enable exploration of PTP BMCA. Each task has tags to allow selective execution. 

tags:

  - trace:       invokes wireskark on the localhost to read tcpdump pipe from a VM
  - stop-all:    stop ptp process on all VM's
  - start-all:   start ptp process on all VM's
  - stop-node1:  stop ptp on node1
  - stop-node2:  stop ptp on node2
  - start-node1: start ptp on node1
  - start-node2: start ptp on node2 
