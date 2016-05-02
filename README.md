# Miovision
Calculating the direction vehicles move by using timestamped region tripwires in an intersection, outlined here: http://coding-challenge.miovision.com/. 

Used: JavaScript, JQuery.
Ignored non-sensical or out-of-bound region transitions.

traffic.html file contains the script, which accesses data.json for vehicle data. Script alerts the number of right, straight, left and U-turns, and redirects to http://coding-challenge.miovision.com/TEST_RESULT_STRING. To test it, modify the contents of data.json, or overwrite data.json with test data. 

Potential improvements:
For vehicles with many points, adding each vehicle object to a heap instead of pushing into vehicle array then sorting.
