## Welcome to my software performance analysis blog

Today, software performance strongly depends on the approriate usage of system hardware and software. 
Unfortunately, efficient software is not generated automatically by compilers in most cases.
Software needs to be tuned (manually) for optimal usage of vector registers, cache memory, multiple cores, GPU accelerators, and network interconnects.  
Without optimization, the total computational performance tends to be even lower than 1% of the theoretical peak performance.    

### Tools
There are tons of tools available that address performance debugging and analysis and I will not got into detail here.
Feel free to use whatever you think is approriate or available in your context. 
In the end, tuning methodology tends to be very similar accross all supportive tools.
I personally have a work affiliation with the tools listed at [VIRTUAL INSTITUTE – HIGH PRODUCTIVITY SUPERCOMPUTING](http://www.vi-hps.org).
This blog documents analysis exmaples taken from my regular work using above performance tools.
I noticed that working with performance tools is not always as easy as one would hope.
Therefore, I want to share my experiences and provide an insight into what's actually possible and how one can get there.

