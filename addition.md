# Addition

Scenario: Addition of two negative numbers
  
  Given - Calculator is on

  When - type in "negative number"

  And - press "plus"
  
  And - type in "negative number"
  
  And - press "equals"
  
  Then- the result is sum of two numbers with -ve sign in front of it

Scenario: Addition of two decimal numbers
  
  Given - calculator is on
  
  When - type in "decimal number"

  And - press "plus"
  
  And - type in "decimal number"
  
  And - press "equals"
  
  Then- output is the sum with decimal point at correct position

Scenario: Typing operators more than once
  
  Given - Calculator is on
  
  When - type in "positive/negative number"

  And - press "plus twice"
  
  And - type in "positive/negative number"
  
  And - press "equals"
  
  Then - see the sum of two numbers as result
  
Scenario: Addition of fractions

  Given The calculater is on
  
  When - type in "1st fraction number"
  
  And - press "plus"
  
  And - type in "2nd fraction number"
  
  And - press "equals"
                      
  Then - see the sum as the result in decimal

Scenario: Addition of +ve and -ve number

  Given The calculater is on
  
  When - type in "positive number"
  
  And - press "plus"
  
  And - type in "negative number"
  
  And - press "equals"
  
  Then - see the sum as the result with the appropriate sign

Scenario: Typing two operator

  Given - The calculater is on
  
  When - type in "negative number"
  
  And - press "plus" and "another operator"
  
  And - type in "negative number"
  
  And - press "equals"
  
  Then - see the result according to the second operator used

Scenario: Addition of more than 2 numbers

  Given- The calculater is on
  
  When - type in "1st number"
  
  And - press "plus"
  
  And - type in "2nd number"
  
  And - press "plus"
  
  And - type in "3rd number"
  
  And - press "equals"
  
  Then - see the sum as the result

Scenario: Adding numbers where the result goes out of range

  Given - The calculater is on
  
  When - type in "1st large number"
  
  And - press "plus"
  
  And - type in "2nd large  number"
  
  And - press "equals"
  
  Then - see the sum till the visibility of screen then right arrow is use to see the whole number

Scenario: 6+* is provided as input?

  Given - The calculater is on
  
  When - type in "1st number"
  
  And - press "plus"
  
  And - type in "multiply"
  
  Then - see the "INVALID INPUT"  as the result
