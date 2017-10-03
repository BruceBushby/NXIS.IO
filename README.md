# NXIS.IO
Linux Infrastructure Services 

Concept project showing the benefits of collecting sysstat 
data as a means to monitor and analyse Unix estates.

# ioserver
Server side: Receives SAR updates from ioclient
             Processes update into InfluxDB

# ioclient
Client side: inotify client sends sar updates to ioserver


