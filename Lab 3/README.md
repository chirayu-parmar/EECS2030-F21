## Lab 2 is The Building Design Problem
**Lab design by Professor Chen-Wei(Jackie) Wang**

This object-oriented program is solving a simplified building design problem, where a building blueprint consists of plans for floors, and each floor plan contains specifications of various units.

#### **The relevant entities involved in this problem:**
- Each ***unit*** is characterized by its intended function (e.g., Master Bedroom, Office) and dimension (width*length). Default measurement, when first creating a unit object, is in feet, whereas a user may request it to be switched to one in meters. Two units are considered equal if their intended functions are the same (case-sensitive) and their areas (in square feet) are the same (even if the dimensions may be different). The formula for conversion: **1 foot is 0.3048 meter**.
- Each ***floor*** is characterized by a maximum capacity (measure in square feet, abbreviated as sq ft) and a list of added units (whose summed amount of space does not exceed, i.e., # LESS-THAN OR EQUAL TO the maximum capacity). A floor may be added up to and including **20 units** to a floor (No need perform error handling for this). In an attempt to add a unit whose space is such that the floor's maximum capacity will be exceed, an exception is expected. Two floors are considered equal if: 
  1. their maximum capacities are the same; and 
  2. their spaces are utilized in the same way (meaning that for each added unit in one floor, we can find its equivalent in the other floor, despite the orders in which units are added to the two floors).
- Each building ***blueprint*** is characterized by the number of floors (of the building under design) and a list of added floor plans. You can assume that the current number of added floor plans always dose not exceed, i.e.,  , the speci ed number of 
oors. Given a blueprint, one may inquire about its completion rate (e.g.,
60% if plans for 3 out of the 5 
oors have been added). One may retrieve the list of 
oor plans added so far,
but the property of composition should be preserved: each of the retrieved 
oor plans is a brand new copy
of the corresponding 
oor object. One may also create a blueprint from another, by copying all the relevant
attributes. To determine whether a shallow copy or a deep copy is needed, consult with the starter tests.

