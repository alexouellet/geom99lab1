# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
?avoid=toll
&depature_time=1674167964
&origin=place_id:ChIJzYwGiTUH1YkR_dplU9bxRRs
&waypoints=place_id:ChIJ8Th-_ugH1YkRORD-1L_bg-w
&destination=place_id:ChIJpQLop9IA1YkRBQDaZhEzASY
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJzYwGiTUH1YkR_dplU9bxRRs",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ8Th-_ugH1YkRORD-1L_bg-w",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpQLop9IA1YkRBQDaZhEzASY",
         "types" : [ "street_address" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.9163369,
               "lng" : -78.68007039999999
            },
            "southwest" : {
               "lat" : 43.9120764,
               "lng" : -78.6949997
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "1.7 km",
                  "value" : 1679
               },
               "duration" : {
                  "text" : "4 mins",
                  "value" : 257
               },
               "end_address" : "182 Wellington St, Bowmanville, ON L1C 1W3, Canada",
               "end_location" : {
                  "lat" : 43.9163369,
                  "lng" : -78.6949997
               },
               "start_address" : "49 Liberty St N, Bowmanville, ON L1C 2L8, Canada",
               "start_location" : {
                  "lat" : 43.9157945,
                  "lng" : -78.68007039999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 193
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 43.915087,
                        "lng" : -78.6822059
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e toward \u003cb\u003eLiberty St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 14\u003c/b\u003e",
                     "polyline" : {
                        "points" : "uh`kGlef_NJf@BD`@hA\\h@DFAJAD@D@Hd@zC@JLv@"
                     },
                     "start_location" : {
                        "lat" : 43.9157945,
                        "lng" : -78.68007039999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 266
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 43.912807,
                        "lng" : -78.68121599999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLiberty St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eDurham Regional Rd 14\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "id`kGxrf_Nl@SbA]v@WfA_@j@QnC_AXI"
                     },
                     "start_location" : {
                        "lat" : 43.915087,
                        "lng" : -78.6822059
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1006
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 136
                     },
                     "end_location" : {
                        "lat" : 43.915404,
                        "lng" : -78.69321699999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "av_kGrlf_N@b@QtA[dCi@~D]jCe@vDc@fD]jCWxBYlBSvAqA~HQjAm@tDm@`EMp@UhBAX@l@"
                     },
                     "start_location" : {
                        "lat" : 43.912807,
                        "lng" : -78.68121599999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "38 m",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 43.9157445,
                        "lng" : -78.69321239999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eScugog St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gf`kGrwh_NQAq@?"
                     },
                     "start_location" : {
                        "lat" : 43.915404,
                        "lng" : -78.69321699999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 176
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 43.9163369,
                        "lng" : -78.6949997
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kh`kGpwh_NAb@?X@J@HBRBN@ZCTEXI\\CHCJINCDABOPQPMNSPSL"
                     },
                     "start_location" : {
                        "lat" : 43.9157445,
                        "lng" : -78.69321239999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "0.7 km",
                  "value" : 670
               },
               "duration" : {
                  "text" : "3 mins",
                  "value" : 155
               },
               "end_address" : "69 King St W, Bowmanville, ON L1C 1R4, Canada",
               "end_location" : {
                  "lat" : 43.9124217,
                  "lng" : -78.691236
               },
               "start_address" : "182 Wellington St, Bowmanville, ON L1C 1W3, Canada",
               "start_location" : {
                  "lat" : 43.9163369,
                  "lng" : -78.6949997
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 176
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 43.9157445,
                        "lng" : -78.69321239999999
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e on \u003cb\u003eWellington St\u003c/b\u003e toward \u003cb\u003eSturrock Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cl`kGvbi_NRMRQLOPQNQ@CBEHOBKBIH]DYBUA[COCSAIAK?Y@c@"
                     },
                     "start_location" : {
                        "lat" : 43.9163369,
                        "lng" : -78.6949997
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 426
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 68
                     },
                     "end_location" : {
                        "lat" : 43.9120764,
                        "lng" : -78.6917861
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eScugog St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kh`kGpwh_Np@?P@VClAa@FCnC_AfAa@j@Sj@S`@OJC@?DCNCJEJCn@ORIb@OJE\\MHE"
                     },
                     "start_location" : {
                        "lat" : 43.9157445,
                        "lng" : -78.69321239999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "24 m",
                        "value" : 24
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 43.9122339,
                        "lng" : -78.69158349999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oq_kGtnh_NGOEGEECEEE"
                     },
                     "start_location" : {
                        "lat" : 43.9120764,
                        "lng" : -78.6917861
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "44 m",
                        "value" : 44
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 43.9124217,
                        "lng" : -78.691236
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mr_kGjmh_N@Q@M?G?ECEECIEKCIA"
                     },
                     "start_location" : {
                        "lat" : 43.9122339,
                        "lng" : -78.69158349999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "uh`kGlef_NNl@`@hA\\h@DFAJ?Jv@hFpFiBzDqAXI@b@m@zEgAjI_CdRqCpQ_CrO?fAcAAA|@BTFb@@ZCTOv@GT_@j@_@`@g@^f@_@^a@^k@VmABUA[Gc@CU@}@bA@VClAa@vCcArBu@zAg@l@QbAYn@Uf@SMWIKEE@Q@UCKOIUE"
         },
         "summary" : "Wellington St",
         "warnings" : [],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
