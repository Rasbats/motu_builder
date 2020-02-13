# motu_builder

Only Windows OS at present.

This helper application is intended to automate the download of netCDF (.nc) files showing tidal currents in the Western European area.

Downloading Copernicus netCDF (.nc) files with motu_builder requires registration with the CMEMS service of Copernicus. Apply here:http://marine.copernicus.eu/services-portfolio/register-now/

When using motu_builder your login/password need to be entered on the form before making the download script. 

These files can be converted to grib format using the CDO program (Climate Data Operators).

A guide to using CDO on Windows is here:
https://opencpn.org/wiki/dokuwiki/doku.php?id=opencpn:supplementary_software:cdo

REQUIREMENTS

    Python [2.7, 3.6 or 3.7] (https://www.python.org/downloads/)
    Motuclient [1.8 or higher] (http://marine.copernicus.eu/faq/what-are-the-motu-and-python-requirements
