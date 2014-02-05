Aerotech_XY_Table
=================

This repository is for the XY table donated to us by the project lab in fall 2013.

The documentation, Solidworks models, and datasheets can be found here.

Upon initial reading of the documentation, the stages are extremely precise, with 2mm/rev 
ballscrews and 2000-4000 steps per revolution stepper motors. I don't know if they come
with an encoder just yet, but my guess is that they do.

Because of their precision, I would recommend that this table be used in a PCB milling 
project. Keep in mind that because of their precision, we possibly cannot use them with
Gen7/RAMPS or any ardruino-based controller. The computing load to send 2000 steps per mm 
would be too high (and that's with no microstepping!). We should consider Smoothieboard 
or a similar product.

-Scott
