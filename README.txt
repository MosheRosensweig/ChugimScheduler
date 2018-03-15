Chugim Scheduler:

Problem:
There are c number of chugim in camp. Each chug can have at most m number of members. Each chug can have a different amount of members. 
Each camper fills out a form selecting their top 3 chug selections. Older campers get highest priority in their selections.
Can you write an algorithm that organizes each camper into a chug on their list?

[A] No. 
- It’s entirely possible and quite likely that some kids will not get into their selected chugim
- Some chugim may not actually pan out
- Some chugim underestimated (or, although it’s unlikely, overestimated) the number of members it can support.

Instead, we will attempt at a good approximation. 