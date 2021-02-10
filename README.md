# DiUS-Coding Challenge

### Shopping Challenge:

* Rules are written in a way that are not dependent on the SKU (Key) and can be used for different products with same deal.

* New rules can be added directly in the Rules Class.

* Pricing Rules Method takes in items dictonary to apply rules according to the logic for calculating total price.

* Checkout class scans the items and retuns the total cost in human readable format.

* Also, added 2 new test cases for understanding different scenarios.

  * Test case #4: This test case uses all rules that are in the problem statement.
  * Test case #5: Contains less number of VGAs and more of MBPs.
  
### Bowling Challenge:

* Created Bowling class that implements all the rules mentioned in the problem statement.

* Rules have been implemented for the last frame (i.e, 10th frame).

* Test cases have been included for the whole game (including optional ones).

* Optional test cases (includes 10 frames):
  
  * Test case #4: Bowler bowls a spare in the last frame.
  * Test case #5: If Strike is scored in the last frame.
  * Test case #6: Total score if bowler bowls a strike in every roll.
