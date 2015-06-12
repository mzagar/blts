Better Living Through Statistics: Monitoring Doesn't Have To Suck.
==================================================================


This is the source code for the demo, plus slide material, that I used when I presented this talk to PuppetConf 2012, again at OSDC 2013, and at PuppetCamp Sydney 2013.

The URL for the video from PuppetConf 2012 is http://youtu.be/eq4CnIzw-pE 

The original slide deck is at https://docs.google.com/presentation/d/1uTLggLR5HICnSyhTJyQWNeYWZ6niHyCsup7wNFByex4/pub

I presented an abridged version to the Sysadmin Miniconf at Linux.conf.au 2014, the revised slide deck is here:

https://docs.google.com/presentation/d/1Dq4eRUlkONnVnnXg6M_ZSi6xBLEwe7kjwjx74vFL1N4/pub

To use the demo code
--------------------

Have Go installed, and perhaps latex, dvips, chaksem, and ImageMagick for the slides, and of course make, so that the Makefile builds some stuff.

You'll also need a shell to launch the servers.sh launcher and load.sh antagoniser; the latter also requires `ab' from the apache webserver tools.

Finally, R to look at demo.R -- I tend to forget how this part works each time I present this -- I think I clag out of a text editor into the R interactive prompt each time.  (As it happens, I run R from Emacs, so it's all just buffers ;-)

Please change the email in the `alert()' function in the demo to actually get an alert.

This code is available under the Apache v2 license.