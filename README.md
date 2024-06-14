A2DISK2 is my version of the Apple2 DISK2 controller. Two versions actually. One with 2x 256-byte proms and another with 2x EPROMs.
The former are really hard to come by and few people can program them. The latter should be easier to find and handle.
Both cards have a switch to swap the 2 drives - thought it might be a nice feature. The EPROM version also has a switch to choose 
from 16-sector or 13-sector disks. Was fun to make, if interested search for  A2DISK2 on GitHub.

Note: The MOSFETs used may be a bit of an overkill, I tried BS170 and they worked too, but the pins are differently arranged. It is also
possible to omit the MOSFETs altogether by removing them and shorting the source and drain pins - especially with the EPROM version
as the EPROMs do not have high consumption and can be left powered all the time.
