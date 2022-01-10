## Lab 2 is The Building Design Problem
**Lab design by Professor Chen-Wei(Jackie) Wang**

This object-oriented program is solving a simplified building design problem, where a building blueprint consists of plans for floors, and each floor plan contains specifications of various units.

#### **The relevant entities involved in this problem:**
- Each ***unit*** is characterized by its intended function (e.g., Master Bedroom, O ce) and dimension (width*length). Default measurement, when first creating a unit object, is in feet, whereas a user may request it to be switched to one in meters. Two units are considered equal if their intended functions are the same (case-sensitive) and their areas (in square feet) are the same (even if the dimensions may be different). You are required to use the following formula for conversion: **1 foot is 0.3048 meter**.
- Each ***floor*** is characterized by a maximum capacity (measure in square feet, abbreviated as sq ft) and a list of added units (whose summed amount of space does not exceed, i.e., less than or equal to the maximum capacity). A floor may be added up to and including **20 units** to a floor (No need perform error handling for this). In an attempt to add a unit whose space is such that the floor's maximum capacity will be exceed, an exception is expected. Two floors are considered equal if: 
  1. their maximum capacities are the same; and 
  2. their spaces are utilized in the same way (meaning that for each added unit in one floor, we can find its equivalent in the other floor, despite the orders in which units are added to the two floors).
-
- Each **health record** is characterized by the name of a patient and a collection of vaccination data. Each data item denotes a dose which the patient received, and it includes information of the vaccine, the name of vaccination site, and the date of vaccination. A receipt may be generated, summarizing the patient's vaccination data.
- Each vaccination site is characterized by its supply (accumulated from various vaccine distributions) and a list of vaccination appointments. The maximum number of available vaccine kinds in a site is **4**, corresponding to the number of vaccines recognized in Canada. When a site is first constructed, a limit is specified to constrain the maximum supply (i.e., number of doses available to be administered). Therefore, for a vaccine distribution to be added to the site, it must be that the vaccine is recognized in Canada, and that adding it will not exceed the pre-set limit. Furthermore, one may inquire about the current supply level for each kind of vaccines, or about the total supply across all kinds.
The maximum number of allowed appointments for each site is always **200**. A patient's appointment request is only accepted if the current supply can afford (despite the kinds). The list of patient appointments is administered on a regular (e.g., daily) basis, by consuming the required doses for those registered patients and resetting/clearing the appointment list for new patients.

###### An Example Vaccine Receipt/Proof
![2 1](https://user-images.githubusercontent.com/90284881/148712385-554e062e-ad11-498d-b94a-2468c085797b.png)
###### Vaccines Recognized in Canada [Link](https://www.canada.ca/en/health-canada/services/drugs-health-products/covid19-industry/drugs-vaccines-treatments/vaccines.html)
![2 2](https://user-images.githubusercontent.com/90284881/148712388-6aba84bc-06c1-4c09-8931-d56fb214cff5.png)

