# samo_exploration_1

* This exploration visualizes the building heights in the City of Santa Monica using the publically availble 2008 Countywide Building Outlines dataset (A 2014 dataset is available, but to agencies and members of the LARIAC (Los Angeles Region Imagery Acquisition Consortium Program)
* The data contained in the `HEIGHT` field is `the height of the highest major feature of the building (not including roof objects like antennas and chimneys)`

###Sources
Data obtained from the [Countywide Building Outlines -2008](http://egis3.lacounty.gov/dataportal/2011/04/28/countywide-building-outlines/)

* Fields in the Dataset (Per descriptions from County)
  * CODE - Building type (either Building or Couryard).  Note that in areas not covered by LAR-IAC courtyards are not tagged as such.
  * BLD_ID - unique building ID
  * HEIGHT - the height of the highest major feature of the building (not including roof objects like antennas and chimneys)
  * ELEV - the elevation of the building
  * AREA - the Roof area
  * SOURCE - the data source (either LARIAC2, Pasadena, Palmdale, or Glendale)
  * DATE - Date Captured (2006, 2008, or blank)
  * AIN - the Parcel ID number.  This was computed from the center of the building.  If a building covers two parcels, only one of the parcels will be captured.  If a building contains many parcels (Condominiums for example) only one of the parcels will be captured.

###Next Steps
* Link this data with the Local Roll of the [LA County Assessor](https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2006-thru-2016/9trm-uz8i) to identify:
 * The year the building was built
 * Type of building (Single Family, Duplex for example)
 * Number of Units (Residential)
 * Other fields within the LA County Assessor
