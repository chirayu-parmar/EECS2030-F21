## Lab 1 is APPLE AppStore Problem
**Lab design by Professor Chen-Wei(Jackie) Wang**

#### **The relevant entities involved in this problem:**
- Each update **log** is characterized by their version (e.g., 5.7.31) and fixes from the earlier version (e.g.,Addressed writing lag issues). A log's fixes are represented as a comma-separated list of string values enclosed within a pair of square brackets (e.g.,[Fix 1, Fix 2]). The maximum number of allowable fixes for an update log is 10.
- Each app is characterized by their name (e.g., GoodNotes 5), a list of update logs (for its various versions), and a list of user rating scores. When submitting a rating score, it is assumed that a value between 1 and 5 is given (and thus there is no need to perform any error handling). When creating an app object, an input
integer is supplied to specify the maximum number of submitted ratings allowed. On the other hand, the maximum number of update logs allowed for an app is always 20. It is expected that when a rating report is demanded for an app, details of its current version and an average of its submitted ratings are included.
