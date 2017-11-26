# 5G: The Next Step in Mobile Communications
*This is a draft ReadMe, outlining basic ideas and topics. During the project I'll use it mainly to discuss progress/ideas and record notes/interesting articles etc, but it will be finalised and changed considerbly before December 1st 2017.*
> Module: Research Methods in Computing & IT / 4th Year Software Development  
> Lecturer: Dr Martin Kenirons

This repository conatins work on two assessments for the Research Methods module - a *Literature Review* and a *Research Presentation*, both on an area of active research. I have chosen to research 5G, the fifth generation of communications technology.

## Word Count
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Section&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Count&nbsp;&nbsp;         |
| -----:|:----------------------:	|--------------:|
|*I*|**Introduction**			| 273&nbsp;&nbsp;&nbsp;             |
|*I.A*| A Brief History			| 194&nbsp;&nbsp;&nbsp;             |
|*I.B*| 4G / Current				| 234&nbsp;&nbsp;&nbsp;             |
|*II*|**Fifth Generation**		| 82&nbsp;&nbsp;&nbsp;              |
|*II.A*| Definition of 5G			| 334&nbsp;&nbsp;&nbsp;             |
|*III*|**Proposed Technologies**	| 54&nbsp;&nbsp;&nbsp;              |
|*III.A*| Millimetre Waves			| 262&nbsp;&nbsp;&nbsp;             |
|*III.B*| Small Cells           	| 356&nbsp;&nbsp;&nbsp;             |
|*III.C*| Massive MIMO              | 231&nbsp;&nbsp;&nbsp;             |
|*III.D*| Beamforming / Spatial Multiplexing        | 282&nbsp;&nbsp;&nbsp;             |
|*IV*| **The Future of 5G**              | 48&nbsp;&nbsp;&nbsp;             |
|		 | Total		            | 2350&nbsp;&nbsp;&nbsp;            |


## Predecessors 
**1G** - the first phones, being able to make a phone call.  
**2G** - slightly smaller devices, could send text messages.  
**3G** - first smartphones, could handle basic internet/webpages etc.  
**4G** - advanced smartphones, very fast - personal tests on phone peak at 70mbps download speed, average at around 15mbps.  

## What is 5G?
No real definition yet (still setting out standards, experts don't even have a proper definition/depends on who you ask) - simply put, a faster and more efficient version of 4G, with different technologies behind it. 5 main technologies - Millimetre Waves, Small Cell, Massive MIMO, Beamforming, and Full Duplex.  

*Following descriptions of technologies based on [IEEE Spectrum video explaining 5G](https://www.youtube.com/watch?v=GEx_d0SjvS0). Will research more & find more technical descriptions but using this as a start to get the basics down, might use these descriptions in presentation.*

### Millimetre Waves
Most smart devices typically only use frequencies between 3-6GHz - more devices = more crowded = slower, network carriers running out of bandwidth. Use other frequencies? Researchers experimenting on shorter *millimetre waves*, which use frequencies 30-300GHz - not used by mobile devices currently, using these freqs would open up more bandwidth for more devices. **The problem:** millimetre waves not as strong as traditional signals, not great through walls/trees/rain etc. How to solve the problem? Small Cell.

### Small Cell
Current way is to broadcast signals for long distances using few cell towers, which won't work for millimetre waves (too many obstacles). Small cell would use thousands of smaller stations which could transmit signals around obstacles - as you move, your device would switch to the station that was closest/strongest.

### MIMO: Multiple Input, Multiple Output
Current 4G stations hold about 12 ports for antennae to handle all traffic. MIMO stations could support 100 ports = way more capacity for traffic. However more ports = more interference (antennae send signals in every direction). Solution? Beamforming.

### Beamforming
Instead of broadcasting in every direction, beamforming allows stations to send a concentrated stream of data in one direction, to specific device - prevents as much interference and is more efficient (not going out in all directions, one direction = less energy etc) meaning more data can be handled at once. MIMO stations would keep track of timing and direction of received signals, use algorithms to detect exactly where the signal came from and plot best route back to device, maybe even bounce off walls or split data packets - again for less interference.

### Full Duplex
Current stations use one-way-at-a-time setup for signals, antennae can only do one job at a time - think of frequency as train track and signal as a train. One train going one way = fine, even two trains going one way = fine. Two trains going opposite ways = obviously not good. Current way is have signals take turns, or put them on different frequencies. Full duplex would use high speed switches, acting like a split in the same "track" that merges back into one track - one signal goes one side, the other uses the other side, signals don't mix but use the same frequency - very efficient, faster, a lot more gets done on the same freq. Very very non technical explaination but general idea is there.

### Current Problems
Mainly to do with infrastructure, either existing or that which needs to be built. Cost of tearing things down + will users have to put up with lack of signal/weak signal? Cost of building - small cell networks require many stations, could be expensive, might not look the best (cities becoming cluttered - more cells due to more buildings), planning permission etc.