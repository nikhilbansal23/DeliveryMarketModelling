# DeliveryMarketModelling


elhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.



Assignment

The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

The company wants to understand and process the data coming out of data engineering pipelines:

Clean, sanitize and manipulate data to get useful features out of raw fields;
Make sense of the raw data and help the data science team to build forecasting models on it.
Data Description

delhivery_data.csv contains records of deliveries prepared by the data engineering department for modeling and has the following columns:

data – tells whether the data is testing or training data

trip_creation_time – Timestamp of trip creation

route_schedule_uuid – unique Id for a particular route schedule

route_type – transportation type:

FTL – Full Truck Load: FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way

Carting – handling system consisting of small vehicles (carts)

trip_uuid - unique ID given to a particular trip (A trip may include different source and destination centers)

source_center – ID of a trip origin point

source_name – the name of a trip origin point

destination_center – destination ID

destination_name – destination Name

od_start_time – trip start time

od_end_time – trip end time

start_scan_to_end_scan – time taken to deliver from source to destination

is_cutoff – unknown field

cutoff_factor – unknown field

cutoff_timestamp – unknown field

actual_distance_to_destination – the distance in kilometers between the source and destination

actual_time – actual time taken to complete the delivery (cumulative)

osrm_time – an open-source routing engine time calculator which computes the shortest path between points in a given map (given usual traffic) and gives the time 

estimate (cumulative)

osrm_distance – an open-source routing engine that computes the distance of the shortest path between points in a given map (cumulative)

factor – unknown field

segment_actual_time – time taken by a segment of the package delivery

segment_osrm_time – the OSRM segment time

segment_osrm_distance – the OSRM distance for a segment

segment_factor – unknown field

Practicalities

Analyze the provided data and provide insights to the best of your abilities. Use statistical tests to support your claims. Include the relevant tables/graphs/visualization to explain what you have learned about the market. Make sure that the solution reflects your entire thought process including the preparation of data - it is more important how the code is structured rather than just the final result or plot.
