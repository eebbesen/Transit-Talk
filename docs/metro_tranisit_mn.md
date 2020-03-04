ftp://ftp.gisdata.mn.gov/pub/gdrs/data/pub/us_mn_state_metc/trans_transit_schedule_google_fd/csv_trans_transit_schedule_google_fd.zip

https://transit.land/feed-registry/operators/o-9zvw-metro

Currently the transitland feed only contains 40 routes, about 11% of the 370 routes operated by Metro Transit. https://transit.land/api/v1/routes?operated_by=o-9zvw-metro&total=true

I've confirmed the gtfs zip for Metro Transit contains all 370 routes, but there appears to be some issue with GTFS compliance per https://transitfeeds.com/p/metro-transit/179/latest/issues and loading using the `set_up_transit` rake task -- I need to rename the transit_schedule_google_feed html and xml files.

