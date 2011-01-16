Configuration
=============
Make sure you change your location code in the conkystats config 
to get accurate weather reports. The location code uses Accuweather's
system. For people in the US it is your zipcode.

Startup
=======
There are 4 conky configuration files in this directory. Each one should 
be passed into conky. For example::

    cd conky
    conky -c conkydate &
    conky -c conkyhr &
    conky -c conkymin &
    conky -c conkystats &

About
=====

This conky theme goes well with the "Nice and Clean" awesome window 
manager theme, which is based off of ghost1227's openbox work.

All credit for this conky theme goes to ghost1227
http://workshop.ghost1227.com/2009/06/two-new-openbox-themes/
