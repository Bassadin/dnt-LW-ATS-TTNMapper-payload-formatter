# dnt-LW-ATS-TTNMapper-payload-formatter
A TTNMapper integration compliant payload formatter for the LoRaWAN GPS Tracker [dnt-LW-ATS](https://www.dnt.de/navigation/86bcf6e985f14a4c8898dd8dbb583dff) from [dnt Innovation GmbH](https://www.dnt.de/)

## Modifications

Main modifications were made in the following [block of code](payload_parser_ttnmapper.js#L85-L104).
The GPS data was moved from the `gnss` sub-object to the top-level of the JSON object.
