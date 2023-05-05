Dev notes:
- Continued operation of ships and crews requires wares periodically.
- Ware types are the same that were used in construction, amount is configurable. Perhaps give option for including or excluding wares that supply ships don't have by default. Or change what supply ships have by default.
- 

How:
- supply ship, add requirements
- every X minutes a ship will need to resupply with wares
- resupply is automatic within a sector
- first take from supply ship in fleet, then nearest supply ship, then player stations prioritizing those that sell everything required,
then from any faction station
- if unable to resupply: warn player, then at NEXT resupply start degrading the parts for which resupply could not be achieved

