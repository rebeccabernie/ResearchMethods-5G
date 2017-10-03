# 5G: The Next Step in Mobile Communications
*This is a draft ReadMe, outlining basic ideas and topics. During the project I'll use it mainly to discuss progress/ideas and record notes/interesting articles etc, but it will be finalised and changed considerbly before December 1st 2017.*
> Module: Research Methods in Computing & IT / 4th Year Software Development  
> Lecturer: Dr Martin Kenirons

This repository conatins work on two assessments for the Research Methods module - a *Literature Review* and a *Research Presentation*, both on an area of active research. I have chosen to research 5G, the fifth generation of communications technology.

## What is 5G?
No real definition yet (still setting out standards, experts don't even have a proper definition/depends on who you ask) - simply put, a faster and more efficient version of 4G, with different technologies behind it. 5 main technologies - Millimetre Waves, Small Cell, Massive MIMO, Beamforming, and Full Duplex.  

### Millimetre Waves
Most smart devices typically only use frequencies between 3-6GHz - more devices = more crowded = slower, network carriers running out of bandwidth. Use other frequencies? Researchers experimenting on shorter *millimetre waves*, which use frequencies 30-300GHz - not used by mobile devices currently, using these freqs would open up more bandwidth for more devices. **The problem:** millimetre waves not as strong as traditional signals, not great through walls/trees/rain etc. How to solve the problem? Small Cell.

### Small Cell
Current way is to broadcast signals for long distances using few cell towers, which won't work for millimetre waves (too many obstacles). Small cell would use thousands of smaller stations which could transmit signals around obstacles - as you move, your device would switch to the station that was closest/strongest.

### MIMO: Multiple Input, Multiple Output
Current 4G stations hold about 12 ports for antennae to handle all traffic. MIMO stations could support 100 ports = way more capacity for traffic. However more ports = more interference (antennae send signals in every direction). Solution? Beamforming.

### Beamforming
Instead of broadcasting in every direction, beamforming allows stations to send a concentrated stream of data in one direction, to specific device - prevents as much interference and is more efficient (not going out in all directions, one direction = less energy etc) meaning more data can be handled at once. MIMO stations would keep track of timing and direction of received signals, use algorithms to detect exactly where the signal came from and plot best route back to device, maybe even bounce off walls or split data packets - again for less interference.




