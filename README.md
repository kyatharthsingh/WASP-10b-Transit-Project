# Transit Photometry of WASP-10b

This project analyses the transit of exoplanet WASP-10b using TESS data.

I downloaded the TESS light curve using Lightkurve and cleaned it by removing NaNs.
The light curve was flattened and then folded at the orbital period.

**Results:**
- Planet: WASP-10b
- Orbital Period: 3.0927 days
- Transit Depth: ~2%
- Transit Duration: ~2.5 hours

The dip in brightness confirms the planet passing in front of its host star.
This method is called Transit Photometry.

**Tools Used:** Python, Google Colab, Lightkurve, Matplotlib, TESS Data
