---
layout: page
title: Engineering
---
Engineering
The BRITE-Constellation satellites are based on a development carried out at the University of Toronto Institute of Aerospace Studies and its [Space Flight Lab (UTIAS-SFL)](https://utias-sfl.net/), in Toronto, Canada. UTIAS-SFL runs a program called Canadian Advanced Nanospace eXperiment (CANX). The BRITE satellites are developed under the [CANX-3 program](https://utias-sfl.net/?page_id=407) which are based on UTIAS-SFL’s Generic Nano-satellite Bus (GNB).
|![bus]({{ site.url }}/img/bus.jpg)
The key engineering challenge for the BRITE satellites is the development of an Attitude Determination and Control System (ADCS) which allows the nanosatellites to be three- axis stabilized to within one minute of arc rms and with an attitude accuracy of at least 10 seconds of arc. This performance is required to allow the positioning of stars in the field of view onto the same detector pixels in order to achieve the needed photometric precision.

# Bus
The BRITE nanosatellite bus, along with the spacecraft structure and its vital subsystems (Figure below) is a 20cm cube with a mass of less than 8kg. It houses three orthogonal reaction wheels and three orthogonal magnetorquer coils for three-axis attitude control and momentum dumping. A magnetometer and six sun sensors provide first order attitude determination. The bus also carries a star tracker which will enable attitude determination to within 10 arcseconds and attitude stability down to one arcminute rms. See the following Table.

|Satellite Specification    |Value
Volume	                    |20x20x20 cm
Mass	                    |<8.0 kg
Attitude Determination	    |10 arcseconds
Attitude Control Accuracy   |Better than 1.0°
Attitude Control Stability  |1 arcminute RMS
Power	                    |5.4 W to 10 W
Bus Voltage	                |4.0 V (nominal)
Battery Capacity	        |5.3 Ah
Data Downlink	            |S-Band (up to 256 Kbps)
Data Uplink	                |UHF
Payload Data Storage	    |Up to 256 MB

Table 1: BRITE satellite bus specifications.

# Science payload
The BRITE nanosatellite science payload of each satellite (Figure below) consists of a five -lens telescope with an aperture of 3 cm and an interline CCD detector from Kodak, aKAI 11002-M, with 11M pixels (see Table below, for specifications). The optical elements are housed inside the optical cell and are held in place by spacers. The photometer has a resolution of about 30 arcseconds per pixel and a field-of-view of 24 degrees. The mechanical design for the blue (390-460nm) and for the red (550-700nm) instrument is nearly identically, but optimized for the respective wavelength range.
|![Telescope]({{ site.url }}/img/telescope.jpg)
The CCD detector was selected based on its low dark current for temperatures at or below +20C. Problems emerged with the CCD when working in space, which were investigated by the PHOTometry Team (PHOTT) and solutions proposed to the constellation management. Details are described in [Data Reduction](../science/data_reduction.md) and in a forthcoming paper by Popowicz, A., et al., 2016.
|![Filters]({{ site.url }}/img/BRITE-Filters.jpg)
The filters were designed such that for a star of 10000K (average temperature for all BRITE target stars) both filters would generate about the same amount of photometric signal. The blue filter covers a wavelength range of 390-460nm and the red filter 550-700nm (see Figure below).


# Communication
Communication with BRITE nanosatellites is presently provided by ground stations in [Toronto](https://utias-sfl.net/?page_id=1759), [Vancouver](https://www.phas.ubc.ca/), [Graz](https://www.tugsat.at/), and [Warsaw](https://www.brite-pl.pl/pliki/main_en.html).

![Tower]({{ site.url }}/img/IKS-TUG_GS-antenna-tower.jpg)

[A description of BRITE-Constellation can be found in this refereed publication (Weiss et al. 2014, PASP, 126, 573).]({{ site.url }}{{ site.baseurl }}/downloads/PASP.pdf)

