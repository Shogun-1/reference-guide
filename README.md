# Project-3
A reference guide, that can be used to store the information about bus routes; a multifile project

**!IMPORTANT!** Before typing any commands, type their quantity, i.e.:  
3  
NEW_BUS 50 2 Stop1 Stop2   
BUSES_FOR_STOP Stop1  
ALL_BUSES  
---END OF THE PROGRAM---

Output:  
50  
Bus 50: Stop1 Stop2  

*Available commands*:
1) NEW_BUS ***bus*** ***stop_count*** ***stop_1*** ***stop_2*** ...:  Adding new route to the reference guide for ***bus*** with ***stop_count*** stops: ***stop_1*** ***stop_2*** etc
2) BUSES_FOR_STOP ***stop***:  Printing all bus numbers, that pass through specified ***stop***
3) STOPS_FOR_BUS ***bus***:  Printing all stops for specified ***bus*** with interchanges (if available) for every stop
4) ALL_BUSES:  Printing all buses with their routes
