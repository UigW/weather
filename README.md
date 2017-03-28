##Weather station with ultrasound anenometer
Measuring windspeed in the Western Isles

The background to this project is the storm which swept over the Western Isles on January 8 2015. The windspeed regularly exceeded 100 mph, and a friend's weatherstation was swept away. My idea was to develop a weather station (windspeed, temperature, air pressure) with no moving parts.

The building blocks:

Air pressure and temperature and dealt with by the GY-68 BMP180 module.

Airspeed will use low cost car parking ultrasound transducers (40 or 56 KHz).

Two pairs of transducers needed: NS and EW

Ultrasound pulse bursts generated by 4060 cmos oscillator counter and gated logic.

Wind speed..... . . . Anenometer head managed by Arduino

Head powered by 5V 200ma solar panel/LiPo battery

Data transmitted to house via two RFM69HW 433Mhz transceiver modules (approx £1 on ebay)

Data analysed, hosted and displayed on RPi - LCD panel gives instant data, web page
