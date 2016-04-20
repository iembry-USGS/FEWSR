# FEWSR

R package that contains the FEWS river, lake, and pond models used to obtain the evapotranspiration from surface waters in power plants.


# Disclaimer

This software is in the public domain because it contains materials that originally came from the U.S. Geological Survey, an agency of the United States Department of Interior. For more information, see the official [USGS copyright policy](http://www.usgs.gov/visual-id/credit_usgs.html#copyright)

Although this software program has been used by the U.S. Geological Survey (USGS), no warranty, expressed or implied, is made by the USGS or the U.S. Government as to the accuracy and functioning of the program and related program material nor shall the fact of distribution constitute any such warranty, and no responsibility is assumed by the USGS in connection therewith.

This software is provided "AS IS."


# Installation

```R
install.packages("FEWSR")
```


# Examples

```R
library(FEWSR)
fewsr(sheet = "Input", type = "pond", output = "csv")
# The sheet name is "Input" and the surface water is pond


fewsr(type = "river", output = "xlsx")
# The sheet number is 1 (default) and the surface water is river


fewsr(sheet = 4, type = "lake", output = "both")
# The sheet number is 4 and the surface water is lake
```
