# LL2NZTM
UPDATE: I've discovered an external API that will do this far better than I can easily code up, but thought I'd leave this here for posterity.
Here's a link to the alternative code: https://github.com/alangi/AppSheet-Coord-Convert

Conversion from NZGD2000 Latitude, Longitude to New Zealand Transverse Mercator 2000 in JavaScript

I worte this to convert from WGS84 to NZTM, but that requires a complex time dependant transformation which I haven't done yet. Will update when I do. 
In the mean time, the LL2NZTM script will convert WGS84 to NZTM with an error probably less than a metre, depending on where in the country the point is.
