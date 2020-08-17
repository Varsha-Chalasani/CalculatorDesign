# Addition

Scenario: Addition of two negative numbers
  
  Given : Calculator charged and turned on

  When : type in negative number followed by another negative number
  
  Then : The result displayed.

Scenario: Addition of fractions
  
  Given  : Calculator charged and turned on, application has
  parenthesis or history feature
  
  When : Type in the fractions with a plus with aptly placed parenthesis
  or type in first fraction and get the decimal, type in the next fraction
  and get the decimal and both decimals
  
  Then : The result displayed in decimal.
  
  Scenario: Addition of positive and negative number
  
  Given  : Calculator charged and turned on
  
  When : put in the positive number, put in a negative sign, put in
  the absolute positive of negative number.
  
  Then : The result displayed.
  
  Scenario: Addition of decimals
  
  Given  : Calculator charged and turned on
  
  When : Put in first decimal, put in the positive sign, put in the second
  decimal.
  
  Then : The result displayed.
  
  Scenario: Typing operator more than once
  
  Given  : Calculator charged and turned on
  
  When : type in first number, type in an operator, type in another
  operator, type in second number.
  
  Then : Display an error.
  
  Scenario:  Addition of more than 2 numbers
  
  Given  : Calculator charged and turned on
  
  When : type in first number, type in plus sign, type in second number,
  type in plus sign, type in third number and so on.
  
  Then : The result displayed.
  
  Scenario: Adding numbers where the result goes out of range
  
  Given  : Calculator charged and turned on
  
  When : Type in first number, type in plus sign, type in second number.
  
  Then : Number of extra digits calculated and displayed as
  a power of ten.
