# Fast Bike profile for [BRouter Android application](http://brouter.de/brouter/) 

( see Brouter-Web [Brouter-web](http://brouter.de/brouter-web/) as web front end)
 
This repository currently profiles for fast bike long distance routing.

Profile preferences:
   * paved roads
   * tertiary roads
   * low traffic
   * no foot way
   * no traffic lights
   * energy optimal ways

Profile is based on `fastbike_lowtraffic.brd` directly from [BRouter](https://github.com/abrensch/brouter)

Related projects\:  
   * [BRouter](https://github.com/abrensch/brouter)
   * [Brouter-web](https://github.com/nrenner/brouter-web)
   * [Poutnikl's trekking profiles (quite sophisticated)](https://github.com/poutnikl/Brouter-profiles)
   * [Zossebart's profiles](https://github.com/zossebart/brouter-mtb)  
   * [Thomas Traber's velomobile profile](https://github.com/ThomasTraber/brouter_profiles_and_testing)
   * [Jacob's city/street profile](https://github.com/utack/utack_brouter_data)
   
## Profiles
### fastbike_longdistance.brf
   * Currently maintained
   * Patched version of Brouter needed which includes _DIV_ command and _uphillmaxbuffercost_ and _downhillmaxbuffercost_ parameters.
   * Patched version of Brouter is available on [Github](https://github.com/simdens/brouter/tree/dev) 

### fastbike_longdistance_legacy.brf
   * Profile for non patched versions of Brouter
   * currently not maintained