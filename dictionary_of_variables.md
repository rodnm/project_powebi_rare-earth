# Dictionary of Variables Used

1. `country`: Country name. Contains string values.
2. `year`: Year. Contains date values in years.
3. `trade value export`: Trade value of exports in dollars. Contains positive integer values.
4. `trade value import`: Trade value of imports in dollars. Contains positive integer values.
5. `trade value delta`: difference between the value of exports minus imports. Contains double values.
6. `delta_log`: logarithm of `trade value delta`. A logical condition is used where, if the value of `trade value delta` is negative, its absolute value is calculated, and the logarithm of the result is calculated with a negative sign. If the value is greater than zero, the logarithm is calculated. Otherwise, if the value is zero, 1 is added and the logarithm is calculated.
