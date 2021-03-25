# GIS Update

## 2020 Highlights
### Tom Kraft
#### Field data collection, deep analysis, mapping, database administration
* Land Protection Server: added about 15 new layers for use in the Land Protection GIS server	
* Transition Plan Updates: 260 facilities updated with gps coordinates and ADA updates where corrective actions have been taken
* PostGIS database: over 300 tables across 8 schemas used in production
* Migrated data to new instance of Web GIS Services (Geoserver): over 80 layers used that feed into maps.cmparks.net
* Identified over 780 parcels for inclusion in the Carbon Credit Area w/aid of Real Estate and Survey
* Pilot: next generation real estate deed boundaries for Bradley Woods Reservation: 384 geometries (unique parcel/deed boundaries)
* Deer management letters prepared for over 3,000 neighboring residents

### Brandon Garman
#### Analysis, Cartography, and 3D Visualization
* Major Projects
  * Remote visit videos
    * Williams property
    * Uthoff property
    * Hawthorne property
  * Lake Erie Water Trail Map
  * Pathfinder Maps
  * Zoo Project Development Planning
* Medium Projects
  * Brighton Park Site Plan
  * Camp Cleveland Map
  * West Creek Conservancy Parcel by Year
  * Big Creek Trail Map update
  * Hawthorne Property - Updated maps and created a covenant for Clean Ohio grant application - Kristen/Stephanie
  * Johnson's Creek - Created a map and a proposed covenant for Clean Ohio grant application - Kristen/Stephanie
  * West Creek - map(s) for WCC to use for their grant application to acquire part of WKYC property - Derek
  * Zoo - possible traffic reconfiguration/back road entrance - Sean
  * Updated Slavic Village Connector maps for Steve Litt's article
  * Astorhurst disc golf map/plan update
  * Brecksville School Easement
  * BUILD Maps
  * Wendy Park Master Plan

### India Johnson
#### Web Development, Linux Systems Administration, Conservation  Support, Drone Pilot
* Linux Administration and Security:
  * Server Maintenance including updates and security
    * Cadence in 2020 increased to monthly and now weekly for security patches across 12 hosts
* Presentations: 
  * Co-Presenter on UN ODM Training Workshop with a dozen UN agencies
  * ODM presentation for Phenome Force (Plant physiology experts)
* Web Development
  * LEAP Native Plants Nursery Map:
    * Update 
    * Rebuild in newer more secure and modern framework
* Drone flights: 60 (20% increase over 2019): 
  * Notable flights
    * Rainforest Dome 
    * Asian Lantern Fest 
    * Wild Winter Lights 
    * Rhino Yard 
    * Wendy Park 
    * CHEERS/Lakefront 
    * Lake Isaac 
    * Williams/Uthoff/Hawthorn proterties 
    * Jaite in CVNP

### Stephen Mather
#### Manager, Innovation, Analysis, Partnerships, Conservation Support, Linux Administration
* Innovation:
  * Initiated with Zoo Conservation and Science first in world zoo digital twins in support of better animal care
  * Initiated Parks Digital Twins test
* Linux Administration
  * Coordinate with ITS security needs for Administration of Linux machines
  * Infrastructure support, Land Protection server
  * Manage and deploy ongoing updates and for public facing services
* Notable Outreach:
  * UN OpenDroneMap Workshop
  * UN Drone Committees
* Innovative project launches
  * maps-api in support of transition to new Cleveland Metroparks App
  * Launch of 3D Trailview Project	
  * Launch of FlyEye, a new sensor type replacing $20k camera types with $1-5k of parts, greater flexibility, and better quality optics

-----------------------------------------------
# Chiefs' meeting update

## Tom
### P&D
  - Walk/bike-shed analysis for 2021: 2018 ACS and 2021 Parcel data loaded to database. Tinkering with disaggregating latest ACS demographics into the latest residential parcel data for use in the analysis.
  - Providing GIS support to Kelly/PROS for Strategic Plan work - ongoing

### Legal
  - Started Rocky River for integrating interior boundaries into GIS (on hold, no updates)
  - Last meeting determined a couple layer changes to Land Protection Server: add EJA, style project areas by project type (connection vs preservation) - incomplete
  - Set Nate up with Fulcrum, troubleshooting getting reservation boundaries updated in Fulcrum (old method is deprecated)

### Updates
  - Switching geoserver data to reference the new database - need to dig into NR, ADA, Historical Resources tabs (there's a lot of overlap between what's already completed from the main print server and land protection server pages)

## App
  - New Attraction categories have been integrated into mapbox icon sets, notably the grouped icon sets which aggregate multiple attractions at a single park site
  - Worked with Linsey on getting data for new attractions and filling in missing data from older attractions (i.e. GPS coordinates, IDs, Activities)
  - To do: push trails/network data update, switch to block icons at all map scales for Attractions

### PARK METRICS
  - 2019 data was completed for Park Metrics by the February deadline
  - Gold Medal Application data request has been compiled and input (2016 and 2020 numbers), only outstanding item is # of boat slips to be wrapped up asap
  - Trail mileage summaries by Reservation still need to be sent to Marketing, will close this out

### NR
  - Data requests for First Energy, awaiting to hear back about data format they can use (not shapefiles)
  - Need to organize a meeting with John, Pat and others to review the layers related to NR on the print server.
  - Request for historical aerials, this will be a longer-term project but for starters CPL has agreed to send high resolution scans (over 300 maps which will need to be georeferenced and stitched together)

### Outside request
  - Need to create a new Fulcrum account for Jake with Outdoor Experiences instead of waiting to pass him an open seat

## Brandon

### Planning Support
* Emerald Necklace Gateway Design Packet
* Red Line Greenway Shared Use Map

### Marketing / Media
- Lakefront Reservation Trail Map

## India

#Infrastructure:
+ Updated and patched all the servers (weekly)
+ Working on using parallel-ssh to automate running update scripts 
+ Reviewed artillery and whitelist for servers

# Programming:
+ Researched relevant Linux certifications and classes; Will begin prepping 
+ Python and ML courses
+ Updated the framework for the Nursery Site Map and pulled din new nurseries
+ Fixed KNIME log analysis workflow

## Stephen

### Infrastructure
* Testing print-to-pdf functionality for Land Protection Datavase
* maps-api work complete for phase 1 of mobile app development

### Funding
* In contract for $42,000 work with World Bank TZ extending previous work for datasets for flood innundation modeling from OpenDroneMap
    * Work continues.
    * Data refinement phase + waiting for addition data from WB team
    * New invoice issued

## Upcoming and Past Travel and Presentations
* NCGIS presentation on algorithms developed for WB project
* Upcoming European Geospatial Union presentation
