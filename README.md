owl-traffic-monitor
===================

Tracks the amount of network traffic and provides overall and per-sensor statistics.
This solver gets packets from a running aggregator and tries to add a packet success
rate attribute to an identifier with a matching sensor attribute. This works well
with the new-sensors solver (https://github.com/romoore/new-sensors) to track
packets from all transmitters, even those not currently assigned to a task.
