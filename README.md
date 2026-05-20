## Installation

Installing Linux on my Dell Latitude 7490 was not straightforward. The laptop would freeze at startup, which made the process frustrating at the very begging.

After some research, I came across a website [H'S Blog](https://b2g.h11e.de/2021/09/dell7490/)that had the exact fix i needed.
It explained that running a modern Linux distro on my Dell 7490 requires adding two kernel options: `i915.enable_dc=0` and `intel_idle.max_cstate=1`. Without these, the system is unstable and freezes on startup.

After installation you should not forget to add the lines in your bootloader's config file.
