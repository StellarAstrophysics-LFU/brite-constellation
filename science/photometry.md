---
layout: page
title: Photometric Observations
---
The strategy of BRITE Constellation is to observe one star field with
typically 15 primary target stars during at least 15 minutes per
satellite orbit and for up to half a year. The point-to-point scatter
(rms noise) of the collected photometric data during that 15min
collection time is about or below 0.001 mag for stars brighter than
4th magnitude. The images are defocussed, as shown in the figure below,
to avoid saturated pixels and reduce jitter noise due to satellite pointing instabilities.

Each satellite has either an instrument sensitive in a red (550 -700 nm)
passband or in a blue (390 – 460 nm) passband.

The unvignetted field of view of both the red and the blue version of
the camera is about 24 degrees in diameter. The images below are full
frame exposures of the Orion field. On top is the red image obtained
by UniBRITE and below of it the blue image recorded by BRITE-Austria,
both December 2013.

![image tooltip here]({{ site.url }}/img/OrionI-BAb_FF.png)

For each of the target stars in the field a subraster section (image data)
of the CCD containing the Point Spread Function (PSF) and sky background
will be transmitted to the ground. The PSFs of both camera types were set
in a round shape with a diameter of about 8 pixels in the middle of the field.
Towards the edges the PSFs progressively deviate from that shape and their
form gets more complex. The figures below show the PSFs from 32 x 32-pixel
raster images that are extracted from the full frame images (as illustrated
in the Figure above) where the top red are from UniBRITE and the bottom blue
from BRITE-Austria. The different shapes of the PSFs depending on their positions
on the CCDs are clearly visible.

![image tooltip here]({{ site.url }}/img/OrionI-UBr_FF.png)
![image tooltip here]({{ site.url }}/img/OrionI-BAb_PSFs.png)

The BRITE photometry is conducted with a KODAK 4008 x 2672 pixels CCD
detector with a plate scale of 30 arcseconds per pixel. A filter mounted
before the entrance aperture of the telescope and a baffle is also placed
in front of the optics ([see the Engineering page](../constellation/engineering.md)).

The properties of the photometric time series are constrained by the
camera exposure time for bright stars and are in the range of 1 to 5 seconds,
collected about 3-4 times per minute and for 15-35 minutes per orbit.
The overall time base of observations of a certain field is limited to
about 180 days constrained by the minimum Sun exclusion angle of 90
degrees from the aperture plane of the telescope. In addition straylight
conditions from the bright Earth have to be also considered.

![image tooltip here]({{ site.url }}/img/BRITE-C_timeseries_properties.jpg)