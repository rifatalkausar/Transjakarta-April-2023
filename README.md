# Transjakarta-April-2023

Transjakarta is a Bus Rapid System (BRT) transportation system with as of today April 2023 have a total route length of 251,2 km making it the world longest route in the world. With a mission of facilitate its customer to commute in their beloved city it is also hope it can improve the air quality index. In 2022 they managed to achieve 1 million customer per day and in 2023 they want to increase their customer to 1.5 miliion per day. In this analysis we going to dig in more about Transjakarta customer so that we can come up with idea on how to achieve their target. 

In the dataset given there's 22 column in which: 
1.    transID: Unique transaction id for every transaction
2.    payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.    payCardBank: Customers card bank issuer name
4.    payCardName: Customers name that is embedded in the card.
5.    payCardSex: Customers sex that is embedded in the card
8.    payCardBirthDate: Customers birth year
9.    corridorID: Corridor ID / Route ID as key for route grouping.
10.    corridorName: Corridor Name / Route Name contains Start and Finish for each route.
11.    direction: 0 for Go, 1 for Back. Direction of the route.
12.    tapInStops: Tap In (entrance) Stops ID for identifying stops name
13.    tapInStopsName: Tap In (entrance) Stops Name where customers tap in
14.    tapInStopsLat: Latitude of Tap In Stops
15.    tapInStopsLon: Longitude of Tap In Stops
16.    stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
17.    tapInTime: Time of tap in. Date and time
18.    tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
19.    tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
20.    tapOutStopsLat: Latitude of Tap Out Stops
21.    tapOutStopsLon: Longitude of Tap Out Stops
22.    stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
23.    tapOutTime: Time of tap out. Date and time
24.    payAmount: The number of what customers pay. Some are free. Some not.
