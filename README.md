# food-order-billing-system

**Overview**

This Python script calculates the bill amount for food delivery based on the type of food, quantity ordered, and distance in kilometers.

**Features**

* Calculates bill amount based on:

   *Food type ("N" for non-veg, default is veg)
  
   *Quantity ordered
  
   *Distance in kilometers
  
* Handles different distance ranges with varying charges.

**Usage**

*Function: calculate_delivery_bill(food_type, quantity_ordered, distance_in_kms)

   *food_type: Type of food ("N" for non-veg, default is veg)
   
   *quantity_ordered: Number of units ordered
   
   *distance_in_kms: Distance in kilometers from the delivery point

**Notes:**

*Ensure distance_in_kms is non-negative.
   
*Charges vary based on distance ranges:
     
     *Less than 4 km: Standard rate
     
     *4 to 6 km: Additional charges apply-
     
     *More than 6 km: Higher additional charges apply
