# Resource Name Requirement

## The problem

    Create a resource name, i.e. username, in linux, that
    
1) Is non person, or computer idenfiable (no tnielsen, bill.gates.001, print-srv01 etc)  
2) Has no confusing letters/numbers like 0oO 1l  
3) Has no naming schema  
4) Has no words that are "bad", "meaningful", "calculator" such as "58008", "ID10T", "lol", "bob", "alice"  
5) Short length (<5 chars)  
6) Support memorization e.g. indirect "New York, USA" in Wikipedia => Latitude	40° 30′ N to 45° 1′ N 
Longitude	71° 51′ W to 79° 46′ W => "dr7"  
7) Not already in use in the organization/directory  

## Solutions
1) Username lists (list of random names matching the requirements)
2) Geohash 32ghs (random - or related to a popular location easy to remember)  
3) Plus Code (random - or related to a popular location easy to remember)
4) Base 32 ghs 4 characters gives 33,000+ usernames
